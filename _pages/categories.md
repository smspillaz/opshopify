---
title: Categories
layout: default
---

<div class="container">
  {% for category in site.categories %}
    <p>{{ category.title }}</p>
  {% endfor %}
  
  test
</div>