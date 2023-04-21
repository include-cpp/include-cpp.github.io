---
layout: home
title: "#include ＜C++＞"
toc: true
---

## CppCon Safety

<ul>
  {% for page in site.pages reversed %}
    {% if page.categories contains 'cppcon' %}
        <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}   <!-- resource-p -->
  {% endfor %}  <!-- page -->
</ul>

{% include_relative conferences/current_funding_campaign.md %}

## Who are we?

`#include <C++>` is a global, inclusive, and diverse community for developers interested in C++. Here, you can find a welcoming space to learn and discuss C++. We also provide resources to create safer, more inclusive, community gatherings.

Our goal is a more welcoming and inclusive C++ community, as expressed in conferences, the committee, industry and so on. We work hard both to make these changes, and to support others such as [conference organisers](/conferences/organising-conferences/), who share our goals.

We believe that a community is only as good as how it treats its most vulnerable members. Therefore, we strive to create a welcoming, safe, and accessible environment. We have a strong [Code of Conduct](/code-of-conduct), which we [enforce](/moderation).

Our primary communication platform is our [Discord server](/discord/). Join us to discuss and learn C++ in a welcoming, inclusive space.

The moderation and administration team includes [Patricia Aas](https://twitter.com/pati_gallardo), [Sy Brand](https://twitter.com/TartanLlama), [Noam Chitayat](https://twitter.com/_Noam), [Kate Gregory](https://twitter.com/gregcons), [Adi Shavit](https://twitter.com/AdiShavit), [Fred Tingaud](https://twitter.com/FredTingaudDev), [Bryce Lelbach](https://twitter.com/blelbach), [Joanna Blackhart](https://twitter.com/joannablackhart).

Everyone who supports our goals, whether a member of any under-represented groups or not, is welcome to participate in any way - see [What can I do?](/what-can-i-do/) Many of our leaders and contributors are allies and we are grateful for all they do. If you want C++ to be more welcoming and inclusive, you'll be welcomed and included.

## What do we do?

We provide:

- A set of [resources](/resources) on diversity and inclusion.
- An inclusive, welcoming space for people to discuss and learn C++.
  - We have a [Discord server: please join](/discord/).
  - We have a [friendly presence at conferences](/conferences/attending-conferences).
- Help for minorities and junior programmers with [scholarships to attend major conferences](/conferences/scholarships). You can apply for scholarships, and donate to them.
- Help for minorities and junior programmers in submitting talks for conferences or job applications.
- A [toolbox](https://github.com/include-cpp/toolboxes/releases/latest) for C++ conferences to improve diversity and inclusion.
- Help for conferences in reaching minority groups with calls for papers, and suggesting candidates to invite to speak and <a class="page-link" href="/conferences/organising-conferences/">running an inclusive conference</a>.
- Help for companies in improving their C++ job advertisements to improve appeal to minority groups.

We are always doing more, and are open to suggestions for new ideas!

### Learn more about us

You can find out more from:

* Sy Brand's DevRelCon London 2019 talk ["Lessons learned creating an inclusive space in a decades old community"](https://devrel.net/community/lessons-learned-creating-an-inclusive-space-in-a-decades-old-community)
* Víctor Moreno's February 2020 MUCplusplus Lightning Talk ["Include C++"](https://www.youtube.com/watch?v=r23ErUGt9mo)

## What can I do?

Thanks for asking - please see [What can I do?](/what-can-i-do/)

## I like your T-Shirts, can I buy one?

Yes. See our <a class="page-link" href="/shop/">Shop</a> page. We have more than just shirts!

## How can we be contacted?
{:.contact}

If you have joined our Discord, you can post in #meta-discord or DM an admin or moderator. Their names are highlighted in red or blue.

You can also reach us either through [Twitter](https://twitter.com/include_cpp), or through the contact form below.

<form action="https://getsimpleform.com/messages?form_api_token=0249c3a7836e7b2532d7d6fe74e61676" method="post">
<fieldset>
<legend>Contact us</legend>

<div>
  <label for="name">Name:</label>
  <input name="name" type="text" id="name">
</div>
<div>
  <label for="email">Email:</label>
  <input name="email" type="email" id="email">
</div>
<div>
  <label for="message">Message:</label>
  <textarea name="message" id="message" cols="50" rows="10"></textarea>
</div>
<div>
  <input name="send" type="submit" value="Send">
</div>
</fieldset>
</form>
