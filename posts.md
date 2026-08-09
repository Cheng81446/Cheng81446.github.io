---
layout: page
title: 所有文章
permalink: /posts/
---

## 📚 全部文章

{% assign all_posts = site.tea_essays | concat: site.tech_notes | concat: site.life_reflections | sort: "date" | reverse %}

<ul>
  {% for post in all_posts %}
    <li>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color: #888;">[{{ post.collection | replace: "tea_essays", "🍵" | replace: "tech_notes", "💻" | replace: "life_reflections", "🧘" }}]</span>
    </li>
  {% endfor %}
</ul>
