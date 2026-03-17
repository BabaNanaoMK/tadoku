---
layout: page
title: tacho
permalink: /categories/tacho/
---

<ul>
  {% for post in site.categories.tacho %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>