---
title: Posts
layout: flat-list
---

<div class="container">
  {% for post in site.posts %}
    <p>{{ post.title }}</p>
  {% endfor %}
</div>