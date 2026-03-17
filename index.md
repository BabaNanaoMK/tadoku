---
layout: default
title: Blog
---

# こんにちは、バナナ です

英語多読に関するよしなしごとを徒然なるままに記載します。

## カテゴリ

<ul class="category-list">
  <li><a href="{{ '/categories/tadoku/' | relative_url }}">多読</a></li>
  <li><a href="{{ '/categories/tacho/' | relative_url }}">多聴</a></li>
  <li><a href="{{ '/categories/takan/' | relative_url }}">多観</a></li>
  <li><a href="{{ '/categories/shadowing/' | relative_url }}">シャドーイング</a></li>
  <li><a href="{{ '/categories/others/' | relative_url }}">他</a></li>
</ul>

## Blog
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">
      {{ post.date | date: "%Y-%m-%d" }} — {{ post.title }}
    </a>
  </li>
{% endfor %}
</ul>
