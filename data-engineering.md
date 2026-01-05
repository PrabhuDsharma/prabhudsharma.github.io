---
layout: page
title: Data Engineering
---

This section covers core data engineering concepts and practices.

Topics include:
- ETL vs ELT
- Data modeling
- Pipelines and orchestration
- Lakehouse patterns
- Batch vs streaming

## Posts

<ul>
{% assign de_posts = site.posts | where_exp: "post", "post.categories contains 'DataEngineering'" %}
{% for post in de_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small> — {{ post.date | date: "%d %b %Y" }}</small>
  </li>
{% endfor %}
</ul>
