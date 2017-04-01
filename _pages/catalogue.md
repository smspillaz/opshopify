---
title: Catalogue
layout: default
---

<div class="container">
  {% for item in site.products %}
    <div class="row">
        <div class="col-md-3">
            <img src="{{ item.image }}" />
        </div>
        <div class="col-md-9">
            <div class="container">
                <h2>{{ item.title }}</h2>
            </div>
        </div>
    </div>
  {% endfor %}
</div>