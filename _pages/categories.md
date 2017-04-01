---
title: Categories
layout: default
---

<div class="container">
    {% for category in site.pcategories %}
    <div class="row content-row">
        <div class="container text-center">
            <h2 class="section-header">{{ category.name }}</h2>
        </div>
        {% for product in site.products %}
        {% if category.products contains product.name %}
        <div class="col-md-4">
            <div class="thumbnail text-center">
                <img src="{{ product.image }}" alt="{{ product.title }} image">
                <div class="caption"></div>
                <h3>{{ product.title }}</h3>
                <p>{{ product.description }}</p>
                <p>{{ product.store }}</p>
            </div>
        </div>
        {% endif %}
        {% endfor %}
    </div>
    {% endfor %}
</div>