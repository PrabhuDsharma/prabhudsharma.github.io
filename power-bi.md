---
layout: page
title: Power BI
---

This section focuses on Power BI modeling, performance, and semantic design.

Topics include:
- Storage modes
- DAX patterns
- Semantic models
- Performance tuning
- Enterprise reporting

## Posts

<ul>
{% assign pbi_posts = site.posts | where_exp: "post", "post.categories contains 'PowerBI'" %}
{% for post in pbi_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small> — {{ post.date | date: "%d %b %Y" }}</small>
  </li>
{% endfor %}
</ul>
