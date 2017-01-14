---
title: posts
permalink: posts
---

<h2>posts 6</h2>

{% for post in site.posts %}
<p>
{{ post.date | date: "%-d %b %Y" }}
<a href="evandekhayser.com" + {{post.url}}>{{post.title}}</a>
</p>
{% endfor %}
