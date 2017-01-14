---
title: posts
permalink: posts
---

<h2>posts 7</h2>

{% for post in site.posts %}
[**{{post.title}}**](http://evandekhayser.com + {{post.url}})    <h6>{{ post.date | date: "%-d %b %Y" }}</h6>
{% endfor %}
