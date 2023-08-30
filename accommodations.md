---
layout: default
title: Accommodations
group: Local Information

hotels:

---

## {{ page.title }}

The conference does not have a room block, but there are many hotels and guest houses in the downtown area.
Any of the lodging search engines should be able to provide you with options.
For location purposes, the venue is at Bargargata 1, 101 Reykjavik, Iceland.

{% for hotel in page.hotels %}
{% include hotel.html expanded=forloop.first %}
{% endfor %}
