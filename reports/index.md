---
layout: home
title: "Reports"
---

<ul>
  {% for page in site.pages reversed %}
    {% if page.categories contains 'report' %}
        <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}   <!-- resource-p -->
  {% endfor %}  <!-- page -->
</ul>
