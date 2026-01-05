This is a public learning journal focused on **Microsoft Fabric**, **Power BI**, and **Data Engineering**.

I write concise, technical explanations based on hands-on work — not marketing summaries.

---

## Learning Tracks

### 🔹 Microsoft Fabric
Architecture, OneLake, Lakehouse vs Warehouse, Direct Lake, and how Fabric components work together.  
[Explore Fabric →](/fabric)

### 🔹 Power BI
Semantic modeling, storage modes, DAX patterns, and performance tuning.  
[Explore Power BI →](/power-bi)

### 🔹 Data Engineering
Core concepts like ETL vs ELT, pipelines, orchestration, and analytics-focused modeling.  
[Explore Data Engineering →](/data-engineering)

---

## Latest Posts

<ul>
{% for post in site.posts limit:5 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small> — {{ post.date | date: "%d %b %Y" }}</small>
  </li>
{% endfor %}
</ul>
