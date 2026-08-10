---
layout: default
title: 首页
---

# 🍃 在代码与茶汤之间，游走的行者。

分享茶文化、技术思考与人生感悟。

## ⭐ 精选文章

{% assign featured_posts = site.tea_essays | where: "featured", "true" %}
{% for post in featured_posts %}
- [{{ post.title }}]({{ post.url }}) {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## 📖 最新文章

{% assign all_posts = site.tea_essays | concat: site.tech_notes | concat: site.life_reflections | sort: "date" | reverse %}

{% for post in all_posts %}
  {% unless post.featured == true %}
    - [{{ post.title }}]({{ post.url }}) {{ post.date | date: "%Y-%m-%d" }}
  {% endunless %}
{% endfor %}
