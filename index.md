---
layout: default
title: "Christoforos Kapsalis - Marketing Engineer & Data Scientist"
description: "Data science and marketing analytics portfolio showcasing machine learning, BI, and statistical analysis projects"
keywords: "Christoforos Kapsalis, greek marketing professionals, marketing analysts in greece, marketing analysts in new york, data science, marketing engineer, marketing analytics, marketing business intelligence, marketing bi, business intelligence, data science portfolio, marketing blog, business data science blog"
author: "Christoforos Kapsalis"
---

# Featured Data Science and BI Projects

<ul class="proj-list">
{% for p in site.projects %}
  <li>
    <a href="{{ p.url | relative_url }}">{{ p.title }}</a><br/>
    <small>{{ p.excerpt | default: "Project summary coming soon." }}</small>
  </li>
{% endfor %}
</ul>
