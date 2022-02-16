<ul>
  {% for post in site.posts %}
    <li>
      <a href="{% link {{ post.url }} %}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
