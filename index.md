---
layout: page
title: org 0x7c00
tagline:
---
{% include JB/setup %}

Welcome to org 0x7c00 blog.

My "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
