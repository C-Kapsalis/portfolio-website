---
layout: blog
title: "Blog - Christoforos Kapsalis"
description: "Insights on marketing analytics, data science, AI regulation, and business intelligence by Christoforos Kapsalis"
permalink: /blog/
author: "Christoforos Kapsalis"
keywords: "Christoforos Kapsalis blog, marketing analytics blog, marketing data insights, business intelligence blog"
---

<ul>
  {% for post in paginator.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

<!-- Pagination links -->
<div class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}" class="previous">Previous</a>
  {% endif %}

  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}" class="next">Next</a>
  {% endif %}
</div>
