---
layout: default
title: 首页
---

# 在代码与茶汤之间游走的行者

分享茶文化、技术思考与人生感悟。

## ⭐ 精选文章

<ul>
  {% assign featured_posts = site.tea_essays | where: "featured", "true" %}
  {% for post in featured_posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color: #888; font-size: 0.9em;">{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>

## 📖 最新文章

<ul>
  {% assign all_posts = site.tea_essays | concat: site.tech_notes | concat: site.life_reflections | sort: "date" | reverse %}
  {% for post in all_posts %}
    {% unless post.featured == true %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span style="color: #888; font-size: 0.9em;">{{ post.date | date: "%Y-%m-%d" }}</span>
      </li>
    {% endunless %}
  {% endfor %}
</ul>
