---
title: Catalogue
layout: flat-list
---

<div class="container">
  {% for item in site.products %}
    <p>{{ item.title }}</p>
  {% endfor %}
</div>