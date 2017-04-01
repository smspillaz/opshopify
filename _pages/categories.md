---
title: Categories
layout: flat-list
---

<div class="container">
  {% for category in site.categories %}
    <p>{{ category.title }}</p>
  {% endfor %}
</div>