---
layout: default
title: 首页
---

# 🍃 在代码与茶汤之间游走

分享茶文化、技术思考与人生感悟。

## 📝 最新文章

{% assign all_posts = site.tea_essays | concat: site.tech_notes | concat: site.life_reflections | sort: "date" | reverse %}

<ul>
  {% for post in all_posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
