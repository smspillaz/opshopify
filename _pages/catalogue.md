---
title: Catalogue
layout: default
---

<div class="container">
    <div class="row content-row">
        {% for product in site.products %}
        <div class="col-md-4">
            <div class="thumbnail text-center">
                <div class="thumbnail-image">
                    <img src="{{ product.image }}" alt="{{ product.title }} image">
                </div>
                <div class="caption"></div>
                <h3>{{ product.title }}</h3>
                <p>{{ product.description }}</p>
                <p>{{ product.store }}</p>
            </div>
        </div>
        {% endfor %}
    </div>
</div>