---
layout: default
title: 标签检索
permalink: /tags/list/
---

# 标签检索
<hr>

{% for tag in site.tags %}
<h3 id="{{ tag[0] }}"># {{ tag[0] }}</h3>
{% for post in tag[1] %}
- {{ post.date | date:"%Y-%m-%d" }} · [{{ post.title }}]({{ post.url }})
{% endfor %}
<hr>
{% endfor %}
