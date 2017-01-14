---
title: posts
permalink: posts
---

<h2>posts</h2>

{% for post in site.posts %}
<div>{{ page.date | date: "%-d %B %Y" }}</div>
{% endfor %}
