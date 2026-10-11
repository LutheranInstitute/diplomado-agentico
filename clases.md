---
layout: default
title: "Clases"
permalink: /clases/
---

[← Portal](../) 

# Clases

<ul>
{% assign clases = site.clases | sort: 'orden' %}
{% for c in clases %}
  <li><strong>M{{ c.modulo }} · {{ c.sesion }}</strong>:
  {% if c.ready %}<a href="{{ c.url | relative_url }}">{{ c.title }}</a>{% else %}{{ c.title }} [en diseño]{% endif %}</li>
{% endfor %}
</ul>
