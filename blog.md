---
layout: page
title: 博客
permalink: /blog/
---

欢迎访问我的博客，这里记录技术笔记、思考与日常反思。

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}</li>
  {% endfor %}
</ul>
