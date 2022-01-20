---
layout: page
permalink: /publications/
title: Publications
nav: true
---


Authors for Operations Research-style entries are listed in alphabetical order. 
The articles below are ordered by <a href="#preprints">pre-prints</a>, <a href="#methods">methodological (machine learning, operations research, information theory) papers</a>, and <a href="#applied">applied (healthcare) papers</a>. 



<div class="publications">


<h2 id="preprints" class="year">Pre-prints/Under review</h2>
{% bibliography -f preprint_papers %}

<h2 id="methods" class="year">Methods</h2>
{% bibliography -f methods_papers %}

<h2 id="applied" class="year">Applied</h2>
{% bibliography -f applied_papers %}


{% comment %}

<h2 class="year">Pre-prints/under review</h2>
{% bibliography -f papers -q @misc %}

<h2 class="year">Journal articles</h2>
{% bibliography -f papers -q @article %}

<h2 class="year">Conference proceedings</h2>
{% bibliography -f papers -q @inproceedings %}


{% endcomment %}

</div>




