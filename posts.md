---
title: posts
permalink: posts
---

<h2>posts</h2>

{% for post in site.posts %}
<p>{{post.date}}  {{post.name}}</p>
{% endfor %}
