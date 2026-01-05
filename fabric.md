---
layout: page
title: Microsoft Fabric
---

This section contains my learning notes and explanations related to Microsoft Fabric.

Topics include:
- Lakehouse and Warehouse
- OneLake architecture
- Data pipelines
- Direct Lake
- Fabric vs Synapse

## Posts

<ul>
{% assign fabric_posts = site.posts | where_exp: "post", "post.categories contains 'Fabric'" %}
{% for post in fabric_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small> — {{ post.date | date: "%d %b %Y" }}</small>
  </li>
{% endfor %}
</ul>
