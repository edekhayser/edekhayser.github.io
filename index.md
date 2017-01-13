{% for post in site.posts limit:1 %}
<h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
<div>{{ post.content }}</div>
{% endfor %}
