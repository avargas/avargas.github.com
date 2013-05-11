---
layout: page
---
<h1>Posts written in english</h1>

<ul class="posts">
  {% for post in site.posts %}
    {% if post.category == 'en' %}
    <li>
      <small class="datetime muted" data-time="{{ post.date }}">{{ post.date | date_to_string }} </small>
      <a href="{{ post.url }}">
        {{ post.title }}<br />
      </a>
    </li>
    {% endif %}
  {% endfor %}
</ul>