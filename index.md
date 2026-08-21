---
layout: default
title: 首页
---

# 🍃 在代码与茶汤之间游走，細述和品嘗生活中的茶香。

分享茶文化、技术思考与人生感悟。

> 中国茶的魅力在于多样性与文化性。每一种茶都有独特的风味与故事。
> 无论是日常饮用的绿茶、红茶，还是收藏价值高的普洱、白茶，都能让人感受到茶文化的深厚底蕴。

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
  {% for post in all_posts limit:5 %}
    {% unless post.featured == true %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span style="color: #888; font-size: 0.9em;">{{ post.date | date: "%Y-%m-%d" }}</span>
      </li>
    {% endunless %}
  {% endfor %}
</ul>
