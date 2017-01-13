{% for post in site.posts limit:1 %}
<a href="{{ post.url }}">{{ post.title }}</a>
<div>{{ post.content }}</div>
{% endfor %}
