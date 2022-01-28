---
layout: page
title: COVID-19 Forecast
description: US weekly COVID-19 forecast with engineered features
img: assets/img/data.jpeg
importance: 1
category: data & cs
---

<a href="https://drive.google.com/file/d/1wpWON0dwaVlqmlYPqJD7YxrNC25m9Yyr/view?usp=sharing">Analysis Source Code Notebook (Colab)</a><br>

COVID-19 pandemic has created the largest public health crisis in decades. Since the outbreak, there has been tremendous interests in attempting to forecast the confirmed cases and the death tolls, and to predict the course of the pandemic, so as to better inform public health policies. In this project, we make use of publicly available data repository on U.S. COVID-19 related statistics in the year of 2020 and 2021 to build a model that forecasts the death tolls in each state in the next week. We engineered and selected time-lagged features, including how the virus spreads geographically between states using the <a href="https://en.wikipedia.org/wiki/Vector_autoregression">Vector Autoregression</a> model and using the proximity method, and experimented on several models including <a href="https://en.wikipedia.org/wiki/Lasso_(statistics)">LASSO</a>, <a href="https://en.wikipedia.org/wiki/Elastic_net_regularization">Elastic Net</a>, <a href="https://en.wikipedia.org/wiki/Random_forest">Random Forest</a>, and <a href="https://en.wikipedia.org/wiki/Gradient_boosting">Gradient Boosting Tree</a>. In particular, we built a <a href="https://en.wikipedia.org/wiki/Ridge_regression">Ridge Regression</a> model that achieves a 94% cross-validation R squared with informative interpretations on the various features contributing to the forecast. We hope that our model can be used in assisting the prediction of the course of the pandemic. 

Below are our presentation slides and report.

<iframe src="https://drive.google.com/file/d/1hRw32r9eAWB699NSg-6j7Gh39EgA-iGD/preview" width="770" height="880" allow="autoplay"></iframe>
<br>
<iframe src="https://drive.google.com/file/d/10zHszJ6d3xaJ_h9k9kwiLxXHiDwRaYQp/preview" width="770" height="1080" allow="autoplay"></iframe>


