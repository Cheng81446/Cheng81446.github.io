---
layout: default
title: 文章列表
---

## 博客文章

这里是我记录生活、茶文化与技术思考的地方。以下是文章目录：

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span> — {{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
