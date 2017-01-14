{% for post in site.posts limit:1 %}
<div>{{ post.content }}</div>
{% endfor %}
