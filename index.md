---
layout: page
title: Microsoft Fabric & Power BI — Learning Blog
---

This blog documents my hands-on learning with Microsoft Fabric and Power BI.

## Posts

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small> — {{ post.date | date: "%d %b %Y" }}</small>
  </li>
{% endfor %}
</ul>
