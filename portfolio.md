---
layout: default
title: "portfolio"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Projects" %}
{% endif %}
