---
layout: page
permalink: /teaching-courses/
title: Courses
description:
years: [Spring 2022, Fall 2021, Fall 2020, Spring 2020, Fall 2019, Spring 2019]
nav: false
heading: Courses
---

Below are listed all the courses that I have taught as the primary instructor since arriving to the US in 2013, with
links to their respective websites.  

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f classes -q @*[year={{y}}]* %}
{% endfor %}

</div>