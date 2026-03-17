---
layout: page
title: tadoku
permalink: /categories/tadoku/
---

<ul>
  {% for post in site.categories.tadoku %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>