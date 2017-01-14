---
title: posts
permalink: posts
---

<h2>posts 6</h2>

{% for post in site.posts %}
<p>
{{ post.date | date: "%-d %b %Y" }} [{{post.title}}](http://evandekhayser.com + {{post.url}})
</p>
{% endfor %}
