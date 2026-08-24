---
layout: page
permalink: /students/
title: Students
nav: true
---

<!-- 
  To add a real headshot: save the photo in assets/img/students/ (e.g., maryam_vahabi.jpg)
  and replace the img src below with {{ '/assets/img/students/maryam_vahabi.jpg' | relative_url }}
-->

<style>
.students.grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}
.students .grid-item {
  width: 160px;
  margin-bottom: 10px;
}
.students .grid-item img {
  display: block;
  margin: 0 auto;
  width: 140px;
  height: 140px;
  object-fit: cover;
  border-radius: 50%;
}
.students .card-body {
  text-align: center;
}
.students .card-title {
  font-size: 1.05rem;
  margin-bottom: 0.25rem;
}
.students .card-text {
  font-size: 0.85rem;
  line-height: 1.3;
}
</style>

<h2 id="current" class="year">Current Students</h2>

<div class="projects grid students">

  <div class="grid-item">
    <div class="hoverable">
      <img src="{{ '/assets/img/students/maryam_vahabi.jpg' | relative_url }}" alt="Maryam Vahabi">
      <div class="card-body">
        <h2 class="card-title">Maryam<br>Vahabi</h2>
        <p class="card-text">PhD, Health Systems<br>2023–</p>
      </div>
    </div>
  </div>

  <div class="grid-item">
    <div class="hoverable">
      <img src="{{ '/assets/img/students/yibo_wang.jpg' | relative_url }}" alt="Yibo Wang">
      <div class="card-body">
        <h2 class="card-title">Yibo<br>Wang</h2>
        <p class="card-text">PhD, DTI<br>2026–</p>
      </div>
    </div>
  </div>

  <div class="grid-item">
    <div class="hoverable">
      <img src="{{ '/assets/img/students/viraj_vardhan.jpg' | relative_url }}" alt="Viraj Vardhan">
      <div class="card-body">
        <h2 class="card-title">Viraj<br>Vardhan</h2>
        <p class="card-text">MSc, Systems Engineering<br>2025–</p>
      </div>
    </div>
  </div>

  <div class="grid-item">
    <div class="hoverable">
      <img src="{{ '/assets/img/students/gaurav_khanal.jpg' | relative_url }}" alt="Gaurav Khanal">
      <div class="card-body">
        <h2 class="card-title">Gaurav<br>Khanal</h2>
        <p class="card-text">MSc, Systems Engineering<br>2026–</p>
      </div>
    </div>
  </div>

</div>


<h2 id="alumni" class="year">Alumni</h2>

<div class="publications">
<ol class="bibliography">
  <li><b>Yibo Wang</b>, MSc, DTI, 2025–2026</li>
  <li><b>Tulika Tahiliani</b>, MSc, Business Analytics, 2024–2025</li>
  <li><b>Morteza Emadi</b>, MSc, Business Analytics, 2024–2025</li>
  <li><b>Joel Vadakken</b>, Undergraduate, NSERC USRA, 2025</li>
  <li><b>Hammad Shakir</b>, MSc, Business Analytics, 2024</li>
  <li><b>Hsuan-Wei Liao</b>, MSc, Business Analytics, 2024</li>
</ol>
</div>
