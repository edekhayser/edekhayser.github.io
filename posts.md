---
title: posts
permalink: posts
---

##posts 6

{% for post in site.posts %}
{{ post.date | date: "%-d %b %Y" }} [{{post.title}}](http://evandekhayser.com + {{post.url}})
{% endfor %}
