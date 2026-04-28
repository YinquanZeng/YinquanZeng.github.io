---
layout: default
title: 首页
---

# 欢迎来到我的主页

## 最新博客文章  

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} · 
<a href="{{ post.url }}">{{ post.title }}</a>
<br>
<span style="opacity:0.7; font-size:0.9rem;">
分类：{{ post.categories | join: ' / ' }}
｜标签：{{ post.tags | join: ' · ' }}
</span>
{% endfor %}
