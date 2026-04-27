---
layout: default
title: 生活随笔
permalink: /category/life/
---

# 生活随笔
<hr>

{% for post in site.categories.life %}
- {{ post.date | date: "%Y-%m-%d" }} · [{{ post.title }}]({{ post.url }})
{% endfor %}
