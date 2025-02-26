---
layout: page
permalink: /publications_chronological/
years: [2025, 2024, 2023, 2022, 2021, 2020, 2018, 2016, 2015]
nav: true
---


Authors for Operations Research-style entries are listed in alphabetical order. 
The articles below are ordered chronologically. 


[**Click here to see papers categorized by methodology versus applications.**]({{ site.baseurl }}{% link _pages/publications.md %})




<div class="publications">


<h2 id="preprints" class="year">Pre-prints/under review</h2>
{% bibliography -f preprint_papers %}


{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}




</div>




