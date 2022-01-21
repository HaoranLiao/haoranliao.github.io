---
layout: page
title: Covid-19
description: US Weekly Covid-19 Forecast
img: assets/img/12.jpg
importance: 1
category: data & cs
---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

---
layout: page
title: project
description: a project with a background image
img: /assets/img/12.jpg
---

<iframe src="https://drive.google.com/file/d/1-6QBwHcB46x2rtJ-qQ1Lk-vGf1gXzfVD/preview" width="780" height="1200" allow="autoplay"></iframe>

    


{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
