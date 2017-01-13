## Welcome

My name is Evan Dekhayser, and I am a senior in high school looking to pursue a career in technology and science.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
