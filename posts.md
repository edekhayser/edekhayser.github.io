---
title: posts
permalink: posts
---

<h2>posts 3</h2>

{% for post in site.posts %}
<p>{{ post.date | date: "%-d %b %Y" }}&#9;&#9;<a href={{post.url}}>{{post.title}}</a></p>
{% endfor %}
