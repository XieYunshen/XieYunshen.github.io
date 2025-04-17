---
layout: home
title: "欢迎来到我的博客"
---

# 欢迎来到我的博客

欢迎来到我的个人博客，这里记录着我的学习笔记、生活点滴和工作经验。

## 最新文章

{% for post in site.posts %}
  {% if forloop.index <= 5 %}  <!-- 只显示最新的5篇文章 -->
    * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
  {% endif %}
{% endfor %}

## 分类

- [博客](#)
- [学习](#)
- [生活](#)
- [工作](#)

## 关于我

...

- [GitHub](https://github.com/XieYunshen)

感谢你访问我的博客，祝你阅读愉快！