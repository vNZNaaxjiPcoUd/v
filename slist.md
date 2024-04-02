---
layout: default
title: short url
---

<br>

<ul>
  {% for p in site.s %}
    <li>
      <p><a href="https://go.jwint.net/{{ p.title | slugify: "ascii" }}">{{ p.title | slugify: "ascii" }}, {{ p.name }} - {{ p.dt }}</a></p>
    </li>
  {% endfor %}
</ul>
