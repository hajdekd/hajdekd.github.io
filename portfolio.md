---
layout: default
title: "Portf"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Skills" %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
