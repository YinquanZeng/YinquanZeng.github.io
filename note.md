---
layout: default
title: 笔记 | Note
permalink: /category/note/
---

# 学习笔记
<hr>

{% for post in site.categories.note %}
- {{ post.date | date: "%Y-%m-%d" }} · [{{ post.title }}]({{ post.url }})
{% endfor %}
