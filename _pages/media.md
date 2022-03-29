---
layout: page
order: 6
permalink: /press/
title: Press
description: 
years: [2021, 2020, 2019, 2018,]
nav: true
heading: Press
---

<!-- _pages/publications.md -->
<div class="publications">


Several of my papers have appeared in major media outlets, an incomplete list is given below.

<br>
<br>

Paper are tagged by their arXiv category and colored as follows:
<span class="badge badge-danger">physics</span> <span class="badge badge-primary">interdisciplinary</span> .


{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f press -q @*[year={{y}}]* %}
{% endfor %}

</div>
