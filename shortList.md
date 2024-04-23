---
layout: small
---

{% for p in site.s %}

- [{{ p.title | slugify }} - {{ p.name }}](https://v.jwint.net{{ p.url }})
  {% endfor %}
