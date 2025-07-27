---
layout: default
title: Projects
---

Welcome! Below is a selection of my graduate‑level data‑science projects.

<ul class="proj-list">
{% assign sorted = site.projects | sort: 'title' %}
{% for proj in sorted %}
  <li>
    <a href="{{ proj.url | relative_url }}">{{ proj.title }}</a><br/>
    <small>{{ proj.excerpt }}</small>
  </li>
{% endfor %}
</ul>
