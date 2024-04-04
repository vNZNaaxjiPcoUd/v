---
layout: slist
title: short url
---
  {% for p in site.s %}

      <a href="https://go.jwint.net/{{ p.title | slugify: "ascii" }}">[{{ p.name }}]  </a>

  {% endfor %}
