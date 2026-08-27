---
title: Contact
nav:
  order: 5
  tooltip:
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are based at the IST Alameda Campus in sunny Lisbon, a vibrant city renowned for its thriving innovation ecosystem, excellent quality of life, and year-round pleasant climate. Our full address: Electronics Scientific Area - North Tower, Av. Rovisco Pais, 1, 1049-001 Lisbon

{%
  include button.html
  type="email"
  text="sagreslab@gmail.com"
  link="sagreslab@gmail.com"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact/map.png"
  link="https://maps.app.goo.gl/eKpWwsu2VrvMgkYf6"
  caption="Click for Google Maps Location"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact/north_tower.webp"
  caption="North Tower @ IST"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


