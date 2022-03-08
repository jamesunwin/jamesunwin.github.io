---
layout: page
order: 2
permalink: /publications/
title: Publications
description: 
years: [2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011]
nav: false
heading: Publications
---

<!-- _pages/publications.md -->
<div class="publications">


 // Loop through all rows, hide those which don't match the selected filter
  for (i = 0; i < rows.length; i++) {
    var abbr = rows[i].getElementsByClassName("abbr")[0];
    if (abbr) {
      var txtValue = abbr.textContent || abbr.innerText;
    var primaryClass = rows[i].getElementsByClassName("primaryClass")[0];
    if (primaryClass) {
      var txtValue = primaryClass.textContent || primaryClass.innerText;
      if (txtValue.indexOf(filter) > -1) {
        rows[i].style.display = "";
      } else {
@@ -53,9 +53,9 @@ function filterSubject(filter) {


My research program is dedicated to the study of physics beyond the Standard Model.   In particular, currently I am especially interested in dark matter, primordial black holes, non-standard cosmological histories, and searches for new particles. 

<br>
<br>

My papers both within physics as well as on other topics, are listed below in reverse chronological order by year. Note that authors on all of my publications appear alphabetically. Citations to my papers can be found on <a href="https://inspirehep.net/authors/1077754?ui-citation-summary=true">Inspire</a>.
Paper are tagged by their arXiv category and colored as follows:
<span class="badge badge-danger">physics</span> <span class="badge badge-primary">interdisciplinary</span> .


{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
