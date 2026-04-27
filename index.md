---
layout: default
title: 首页
---

# 欢迎来到我的主页
---
## 最新博客文章  

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }}
  [{{ post.title }}]({{ post.url }})
  <span style="opacity:0.7;">｜{{ post.categories }}</span>
{% endfor %}
