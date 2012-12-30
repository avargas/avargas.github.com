---
layout: page
title: Welcome
tagline: Personal Blog of Angelo Vargas, a freelance software developer living in the states.
---
{% include JB/setup %}

This is the personal blog of [Angelo Vargas](http://twitter.com/trukin)


As the new year approaches (2013), I've decided I'm going to create a blog.  I will be blogging once a week about a random subject, probably about the Internet and a new technology or something like that. We'll see ...


## Latest posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Networks & How to contact me
<ul class="social">
  <li class="twitter">Twitter <a href="http://twitter.com/trukin">@trukin</a></li>
  <li class="skype">Skype <a href="skype:angelo.d.jesus.vargas">angelo.d.jesus.vargas</a></li>
  <li class="email">Email and GTalk: <a href="mailto:angelo@nivler.com">angelo@nivler.com</a></li>
  <li class="github">GitHub: <a href="http://github.com/avargas">avargas</a></li>
  <li class="github">LinkedIn: <a href="http://www.linkedin.com/in/angelovargas">angelovargas</a></li>
</ul>