---
layout: page
title: 张建龙的学习记录
tagline: 
---
{% include JB/setup %}

我的文章列表
------------
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



