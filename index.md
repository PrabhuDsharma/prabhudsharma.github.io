---
layout: page
title: Microsoft Fabric & Power BI — Learning Blog
---

This is a public learning journal focused on **Microsoft Fabric**, **Power BI**, and **Data Engineering**.

I write concise, technical explanations based on hands-on work — not marketing summaries.

---

<div class="section">
<h2>Learning Tracks</h2>

<div class="track">
  <div class="track-title">Microsoft Fabric</div>
  <p>
    Architecture, OneLake, Lakehouse vs Warehouse, Direct Lake, and how Fabric
    components work together.
  </p>
  <a href="/fabric">Explore Fabric →</a>
</div>

<div class="track">
  <div class="track-title">Power BI</div>
  <p>
    Semantic modeling, storage modes, DAX patterns, and performance tuning.
  </p>
  <a href="/power-bi">Explore Power BI →</a>
</div>

<div class="track">
  <div class="track-title">Data Engineering</div>
  <p>
    Core concepts like ETL vs ELT, pipelines, orchestration, and analytics-focused
    modeling.
  </p>
  <a href="/data-engineering">Explore Data Engineering →</a>
</div>

</div>

---

<div class="section">
<h2>Latest Posts</h2>

<ul>
{% for post in site.posts limit:5 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small> — {{ post.date | date: "%d %b %Y" }}</small>
  </li>
{% endfor %}
</ul>

</div>
