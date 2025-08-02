---
layout: default
title: Projects
description: "Data science and marketing analytics portfolio showcasing machine learning, BI, and statistical analysis projects"
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
