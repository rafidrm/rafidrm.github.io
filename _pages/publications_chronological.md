---
layout: page
permalink: /publications_chronological/
years: [2022, 2021, 2020, 2018, 2016, 2015]
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




{% comment %}

<h2 id="preprints" class="year">Pre-prints/Under review</h2>
{% bibliography -f preprint_papers %}

<h2 id="methods" class="year">Methods</h2>
{% bibliography -f methods_papers %}

<h2 id="applied" class="year">Applied</h2>
{% bibliography -f applied_papers %}



<h2 id="preprints" class="year">Pre-prints/under review</h2>
{% bibliography -f papers -q @misc %}

<h2 id="journals" class="year">Journal articles</h2>
{% bibliography -f papers -q @article %}

<h2 id="conferences" class="year">Conference proceedings</h2>
{% bibliography -f papers -q @inproceedings %}

{% endcomment %}


</div>




