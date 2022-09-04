---
layout: home
title: "Our Communications"
---

<ul>
  {% for page in site.pages reversed %}
    {% if page.categories contains 'communication' %}
        <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}   <!-- resource-p -->
  {% endfor %}  <!-- page -->
</ul>
