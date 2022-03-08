---
layout: page
permalink: /events/
title: Events
description:  
years: [2020, 2019, 2018, 2017, 2016, 2015, 2014]
nav: false
heading: Events organized
---


<div class="publications">


 


{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f events -q @*[year={{y}}]* %}
{% endfor %}

</div>

