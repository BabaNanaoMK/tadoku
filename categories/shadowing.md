---
layout: page
title: shadowing
permalink: /categories/shadowing/
---

<ul>
  {% for post in site.categories.shadowing %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>