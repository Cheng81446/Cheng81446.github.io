---
layout: page
title: 文章归档
permalink: /archive.html
---

## 📚 全部文章

{% assign all_posts = site.tea_essays | concat: site.tech_notes | concat: site.life_reflections | sort: "date" | reverse %}

<ul>
  {% for post in all_posts %}
    <li>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color: #888; font-size: 0.9em;">
        [{{ post.collection | replace: "tea_essays", "🍵 茶事随笔" | replace: "tech_notes", "💻 技术笔记" | replace: "life_reflections", "🧘 生活感悟" }}]
      </span>
    </li>
  {% endfor %}
</ul>

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
