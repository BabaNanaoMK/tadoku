---
layout: page
title: takan
permalink: /categories/takan/
---

<ul>
  {% for post in site.categories.takan %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>