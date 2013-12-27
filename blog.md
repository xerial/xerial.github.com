---
layout: blog
---

{% for post in site.posts limit: 5 %}

<h3>{{ post.title }} <small>{{ post.date | date:"%Y-%m-%d" }}</small></h3>

{{ post.content }}
<hr>

{% endfor %}
