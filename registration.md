---
layout: default
title: Registration Information

registrations:
  fees:
    - type: ACM Member Full Registration
      price: ["$450", "$500"]
    - type: Non-Member Full Registration
      price: ["565", "$625"]
    - type: ACM Student Member Registration
      price: ["300", "$375"]
    - type: Student Non-Member Registration
      price: ["375", "$470"]
---

## Registration Information

<div class="border ui-corner-all ui-shadow">
  <table class="sponsorlevels">
    <tbody>
      <tr>
        <th style="text-align:left"></th>
        <th>Before September 18, 2023</th>
        <th>After September 18, 2023</th>
      </tr>
      {% for reg in page.registrations.fees %}
      <tr>
        <th style="text-align:left">{{ reg.type }}</th>
        <td> {{ reg.price[0] }} </td>
        <td> {{ reg.price[1] }} </td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
</div>


**Note**: ACM requires that we charge 22% Value Added Tax on the above fees.  This is outside the conference budget and we have no control over it.


[Online registration](https://cvent.me/9DEyK5){: data-role="button" class="button" }

In case of problems with registration or billing, please contact [General Chairs](mailto:icn23-chairs@sigcomm.org).


### A Special Note on Author Registration Policy

- Each accepted full-paper/short-paper/workshop-paper/poster/demo must be accompanied by a Full Registration. Each Conference Registration can cover multiple full papers, short papers, posters, or demos.

- Registration accepts Visa, MasterCard, American Express.
