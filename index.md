---
layout: page
title: 页面无法打开
header: Writings and Change
---

##### 用文字记录自己的灵感和曾经的快乐时光.

#### 最近发布的文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>