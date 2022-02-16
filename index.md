<ul>
  {% for post in site.posts %}
    <li>
      <a href="/jekyllsitetest/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
