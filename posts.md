---
title: posts
permalink: posts
---

<h2>posts 1</h2>

{% for post in site.posts %}
<p>{{ page.date | date: "%-d %B %Y" }}</p>
{% endfor %}
