---
layout: page
title: Exploring Io
tagline: haaakons blog on development, astronomy, etc
---

{% include JB/setup %}
page.content
<ul class="posts">
  {% for post in site.posts %}
  <h1><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h1>
  {% post.content %}
  <!---  <li><span>{{ post.date | date_to_string }}</span> &raquo; </li> -->
  {% endfor %}
</ul>


