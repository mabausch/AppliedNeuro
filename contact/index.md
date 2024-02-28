---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Connect with us to learn more about our work or explore PhD and thesis opportunities in our dynamic research environment.

{%
  include button.html
  type="email"
  text="contact us"
  link="marcel.bausch.ukb@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="0228 287 16912"
  link="+49228 287 16912"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/a3whrcmz5FuJ9V2D8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/epi_building.png"
  caption="Epileptologie Bonn"
  link="https://www.ukbonn.de/epileptologie"
%}

{% endcapture %}

{% include cols.html col1=col1 %}

{% include section.html dark=true %}


