---
layout: main
title: Homepage
permalink: /
---

<ul>
  {% for product in site.pink_sapphire %}
  <li>
    <img src="{{ product.first_image_url }}" alt="">
    <p>{{ product.description }}</p>
  </li>
  {% endfor %}
</ul>