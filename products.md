---
layout: archive
title: Products
permalink: /products/
---

<div class="grid__wrapper">
{% for p in site.products %}
  <div class="archive__item">
    <h2><a href="{{ p.url | relative_url }}">{{ p.title }}</a></h2>
    <p>{{ p.subtitle }}</p>
  </div>
{% endfor %}
</div>
