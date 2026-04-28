---
layout: default
title: 全部标签
permalink: /tags/
---

# 全部标签
<hr>

{% for tag in site.tags %}
{% assign tag_name = tag[0] %}
{% assign tag_count = tag[1].size %}
- <a href="/tags/list/#{{ tag_name }}"># {{ tag_name }}</a>
  <span style="opacity:0.7;">({{ tag_count }})</span>
{% endfor %}
