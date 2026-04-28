---
layout: default
title: 生活 | Life
permalink: /category/life/
---

# 生活 随笔
<hr>

{% for post in site.categories.life %}
- {{ post.date | date: "%Y-%m-%d" }} · [{{ post.title }}]({{ post.url }})
{% endfor %}
