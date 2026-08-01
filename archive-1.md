---
layout: page
title: 文章归档
permalink: /archive.html
---

## 全部文章

<ul>
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="post-category">[{{ post.categories | join: ', ' }}]</span>
    </li>
  {% endfor %}
</ul>

---

## 按分类归档

{% assign categories = site.categories | sort %}
{% for category in categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li>
        <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% endfor %}
