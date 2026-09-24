---
layout: page
title: Projects
permalink: /projects/
description: Short descriptions with slides on my papers
nav: true
nav_order: 3
display_categories: [talk, physics, data & cs]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>

<script>
  // Morph the clicked card's title into the project page heading, and back again
  // on return (cross-document View Transitions; a no-op where unsupported).
  (function () {
    var heading = document.querySelector(".post-title");

    function cardTitleFor(url) {
      if (!url) return null;
      var path = new URL(url, location.href).pathname;
      var link = Array.prototype.find.call(document.querySelectorAll(".projects a"), function (a) {
        return a.pathname === path && a.querySelector(".card-title");
      });
      return link ? link.querySelector(".card-title") : null;
    }

    function reset() {
      if (heading) heading.style.viewTransitionName = "";
      document.querySelectorAll(".projects .card-title").forEach(function (t) {
        t.style.viewTransitionName = "";
      });
    }

    function pair(title) {
      if (!title) return false;
      if (heading) heading.style.viewTransitionName = "none";
      title.style.viewTransitionName = "page-title";
      return true;
    }

    window.addEventListener("pageswap", function (e) {
      if (e.viewTransition && e.activation && e.activation.entry) {
        pair(cardTitleFor(e.activation.entry.url));
      }
    });

    window.addEventListener("pagereveal", function (e) {
      reset();
      var from = window.navigation && navigation.activation && navigation.activation.from;
      if (e.viewTransition && from && pair(cardTitleFor(from.url))) {
        e.viewTransition.finished.finally(reset);
      }
    });
  })();
</script>
