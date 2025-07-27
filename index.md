---
layout: default
title: Projects
---

Welcome! Below is a selection of my graduate‑level data‑science projects.

<ul>
{% for proj in site.projects %}
  <li>
    <a href="{{ proj.url | relative_url }}">{{ proj.title }}</a> – {{ proj.excerpt }}
  </li>
{% endfor %}
</ul>
