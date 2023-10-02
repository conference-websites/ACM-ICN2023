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


### Registration Instructions for Wednesday's Joint ICN/ICNP panel

To promote cross-fertilization of the communities, the organizers have planned a joint ACM ICN/IEEE ICNP panel on 'Network Abstractions for Continous Innovation - What do We Need?' Wednesday afternoon.
A fee of US$40 members ($48 nonmembers) covers the cost of the venue and post-panel reception.
To register for the panel session and reception, go to the [ICNP Registration site](https://cvent.me/qwQdMy) and choose your appropriate category (member/nonmember).
Fill out the name/demographics questions to get to the **'Registration Options'** page.
Select **"Workshop and Panels Registration/A la Carte"** and click **"Next"**.
Then Choose **'Panel Only'** and complete the payment process.
