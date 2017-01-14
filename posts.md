---
title: posts
permalink: posts
---

<h2>posts 2</h2>

{% for post in site.posts %}
{{ page.date | date: "%-d %B %Y" }}
{% endfor %}
