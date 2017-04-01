---
title: Catalogue
layout: flat-list
---

<div class="container">
  {% for item in site.items %}
    <p>{{ item.title }}</p>
  {% endfor %}
</div>