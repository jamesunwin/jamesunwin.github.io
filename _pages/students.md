---
layout: page
permalink: /students/
title: Students
description:  
years: [UIC, PRIMES-MIT]
nav: false
heading: Students
---

<div class="publications">

In the last decade I have mentored students at many different levels. Below is a list of my former and current students, both graduate PhD students and high school students performing undergraduate research experience in association with  MIT's PRIMES programme. 
 
 <br>
 <hr>
<span style="font-size:15px">

<h2>Current</h2>
 
 {%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f current -q @*[year={{y}}]* %}
{% endfor %}

  <br>

 <hr>
<span style="font-size:15px">

<h2>Former</h2>

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f past -q @*[year={{y}}]* %}
{% endfor %}

 
