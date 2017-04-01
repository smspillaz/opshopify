---
title: Posts
permalink: "/posts"
layout: default
---

<div class="container">
  {% for post in site.posts %}
  <a href='{{ post.url | prepend: site.baseurl}}'>
    <div class="row content-item">
      <div class="col-md-4 col-xs-4 content-row-thumbnail" style="background-image: url('{{ post.image }}')">
      </div>
      <div class="col-md-8 col-xs-8">
        <h2>{{ post.title }}</h2>
      </div>
    </div>
  </a>
  {% endfor %}
</div>