---
layout: default
title: Projects
---

<ul>
{% for p in site.data.projects %}
  <li>
    <a href="{{ p.path | relative_url }}">{{ p.title }}</a><br/>
    <small>{{ p.blurb }}</small>
  </li>
{% endfor %}
</ul>
