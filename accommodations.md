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

There are a lot of hotels available within 25 minute walking, weather condition permitting:
<iframe src="https://www.google.com/maps/embed?pb=!1m26!1m12!1m3!1d16168.860943677706!2d-21.95409269984373!3d64.13970304564658!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m11!3e2!4m3!3m2!1d64.1454001!2d-21.924490799999997!4m5!1s0x48d60bcf00b6dc9b%3A0x513c66fadcdf2e8c!2sGr%C3%B3ska%20-%20innovation%20and%20business%20growth%20center%2C%20Bjargargata%20102%2C%20Reykjav%C3%ADk%2C%20Iceland!3m2!1d64.1363385!2d-21.9470037!5e0!3m2!1sen!2sus!4v1693588380967!5m2!1sen!2sus" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d12553.398703868044!2d-21.94376599774414!3d64.14239958335034!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1sHotels%20near%20Gr%C3%B3ska%2C%20Reykjav%C3%ADk!5e0!3m2!1sen!2sus!4v1693588039522!5m2!1sen!2sus" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>


{% for hotel in page.hotels %}
{% include hotel.html expanded=forloop.first %}
{% endfor %}
