---
layout: small
---
{% for p in site.s %}
[{{ p.title }} - {{ p.name }}](https://v.jwint.net{{ p.url }})
{% endfor %}
