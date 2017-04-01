---
title: Posts
permalink: "/posts"
layout: default
---

<div class="container">
  {% for post in site.posts %}
    <p><a href='{{ post.url | prepend: site.baseurl}}'>{{ post.title }}</a></p>
  {% endfor %}
</div>