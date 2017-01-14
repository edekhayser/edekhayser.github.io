---
title: posts
permalink: posts
---

<h2>posts</h2>

{% for post in site.posts %}
<p>{{ page.date | date_to_long_string }}  {{post.name}}</p>
{% endfor %}
