---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the [Department of Bioengineering](), at [Ege university]().
We are located on the 2th floor of the [Department of Bioengineering]().

{%
  include link.html
  type="email"
  icon=""
  text="yasinkaymaz@gmail.com"
  tooltip=""
  link="yasinkaymaz@gmail.com"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Ege+%C3%9Cniversitesi+M%C3%BChendislik+Fak%C3%BCltesi+Biyom%C3%BChendislik+B%C3%B6l%C3%BCm/@38.4551887,27.2303857,17z/data=!3m1!4b1!4m6!3m5!1s0x14b97ccfe209efdb:0xfdc283d604de1a62!8m2!3d38.4551845!4d27.2325744!16s%2Fg%2F11c6db9p4g"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

Ege Üniversitesi Kampüsü 35100
Bornova-İZMİR 
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/EgeUni.jpg"
  caption="Ege University"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/BiyoMuhEge.jpg"
  caption="Department of Bioengineering"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
