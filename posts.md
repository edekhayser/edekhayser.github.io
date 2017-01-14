---
title: posts
permalink: posts
---

<h2>posts</h2>

{% for post in site.posts %}
<p>{{ page.date | date: "%-d %B %Y" }}</p>
{% endfor %}
