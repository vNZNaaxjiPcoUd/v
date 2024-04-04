---
layout: slist
title: short url
---
{% for p in site.s %}
[{{ p.name }}](https://go.jwint.net/{{ p.title | slugify: "ascii" }})
{% endfor %}
