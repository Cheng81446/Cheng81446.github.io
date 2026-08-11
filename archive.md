---
layout: page
title: 文章归档
permalink: /archive.html
---

---

## 📂 按分类归档

### 🍵 茶事随笔
<ul>
  {% for post in site.tea_essays %}
    <li>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### 💻 技术笔记
<ul>
  {% for post in site.tech_notes %}
    <li>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### 🧘 生活感悟
<ul>
  {% for post in site.life_reflections %}
    <li>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
