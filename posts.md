---
title: posts
permalink: posts
---

<h2>posts 2</h2>

{% for post in site.posts %}
<p>{{ post.date | date: "%-d %B %Y" }}</p>
{% endfor %}
