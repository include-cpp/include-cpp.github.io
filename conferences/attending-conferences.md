---
layout: archive
title: Attending Conferences
---

Since our founding, `#include <C++>` members have been attending conferences and working to make them more inclusive.

![#include <C++> members at CPPP 2019](/images/cppp_2019.jpg)

## Conference Tables

We typically have a table or exhibit booth, where we sell <a class="page-link" href="/shop/">merchandise</a>, give away stickers, and answer questions about inclusion and diversity. This table is generally a great place to meet other attendees who you can be confident will be welcoming and friendly.

![Table at ACCU 2023](/images/table_at_accu_2023.jpg)

## CppCon Safety

We have supported CppCon in the past, but due to continued disagreements with their handling of a serious situation, we no longer do.

<ul>
  {% for page in site.pages reversed %}
    {% if page.categories contains 'cppcon' %}
        <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}   <!-- resource-p -->
  {% endfor %}  <!-- page -->
</ul>
