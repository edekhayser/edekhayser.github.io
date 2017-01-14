---
title: posts
permalink: posts
---

<h2>posts 5</h2>

{% for post in site.posts %}
<p>
({{ post.date | date: "%-d %b %Y" }})
<a href={{post.url}}>{{post.title}}</a>
</p>
{% endfor %}
