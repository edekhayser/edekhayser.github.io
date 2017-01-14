---
title: posts
permalink: posts
---

##posts 7

{% for post in site.posts %}
{{ post.date | date: "%-d %b %Y" }} [{{post.title}}](http://evandekhayser.com + {{post.url}})
{% endfor %}
