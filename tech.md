---
layout: default
title: 技术 | Tech
permalink: /category/tech/
---

# 技术 专栏
<hr>

{% for post in site.categories.tech %}
- {{ post.date | date: "%Y-%m-%d" }} · [{{ post.title }}]({{ post.url }})
{% endfor %}
