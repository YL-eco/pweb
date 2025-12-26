---
layout: default
title: Home
---

{% include nav.html %}

<div class="hero">
  <img src="/assets/img/profile.jpg" alt="{{ site.author.name }}" class="avatar">
  <div>
    <h1>{{ site.author.name }}</h1>
    <p class="small">
      <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a> ·
      <a href="{{ site.author.ssrn }}">SSRN</a> ·
      <a href="https://github.com/yifeiluo">GitHub</a>
    </p>
    <p>{{ site.description }}</p>
  </div>
</div>

<div class="section">
  <h2>Research</h2>
  <p><a href="/research">Working papers and abstracts</a></p>
</div>

<div class="section">
  <h2>Code</h2>
  <p><a href="/code">Selected research code and software</a></p>
</div>

<div class="section">
  <h2>CV</h2>
  <p><a href="/assets/cv/yifei_luo_cv.pdf">Download PDF</a></p>
</div>

<footer>Last updated: {{ site.time | date: "%Y-%m-%d" }}</footer>
