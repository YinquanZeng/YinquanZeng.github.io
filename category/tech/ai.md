---
layout: default
title: 技术 / AI
permalink: /category/tech/ai/
---

# AI 人工智能 专题
<hr>

{% for post in site.categories.tech %}
{% if post.categories[1] == "ai" %}
- {{ post.date | date: "%Y-%m-%d" }} · [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}
