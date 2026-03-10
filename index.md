---
layout: page
title: Microsoft Fabric & Power BI — Learning Blog
---

Hi, I'm **Prabhudeep Sharma** — Senior Analytics Consultant and Microsoft Certified Power BI & Fabric professional
with 3+ years of experience delivering enterprise analytics across Pharma, Manufacturing, and Financial Services.

This is my public learning journal on **Microsoft Fabric**, **Power BI**, and **Data Engineering** —
concise, hands-on technical content based on real project work.

<div class="section">
  <div class="track">
    <a href="/about"><strong>About Me →</strong></a>
    <p>Background, skills, certifications, and education.</p>
  </div>
  <div class="track">
    <a href="/projects"><strong>Projects →</strong></a>
    <p>Real-world case studies across manufacturing, FMCG, and financial services.</p>
  </div>
  <div class="track">
    <a href="/vlog"><strong>Vlog →</strong></a>
    <p>Video walkthroughs and tutorials on Fabric and Power BI.</p>
  </div>
</div>

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
