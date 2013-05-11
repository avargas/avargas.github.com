---
layout: page
---

<h1>Publicaciones en español</h1>

<ul class="posts">
  {% for post in site.posts %}
    {% if post.category == 'es' %}
    <li>
      <small class="datetime muted" data-time="{{ post.date }}">{{ post.date | date_to_string }} </small>
      <a href="{{ post.url }}">
        {{ post.title }}<br />
      </a>
    </li>
    {% endif %}
  {% endfor %}
</ul>