---
title: posts
permalink: posts
---

<h2>posts 3</h2>

{% for post in site.posts %}
<p>{{ post.date | date: "%-d %b %Y" }}    {{post.title}}</p>
{% endfor %}
