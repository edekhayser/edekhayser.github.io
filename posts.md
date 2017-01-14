---
title: posts
permalink: posts
---

<h2>posts</h2>

{% for post in site.posts %}
<div>{{ page.date | date_to_long_string }}</div>
{% endfor %}
