---
layout: blog
title: Blog
---

{% for post in site.posts limit: 5 %}

<h3><a href="{{post.url}}">{{ post.title }}</a> <small>{{ post.date | date_to_long_string }}</small></h3>
{{ post.content }} 
<hr>
{% endfor %}
