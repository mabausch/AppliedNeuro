---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="marcel.bausch.ukb@gmail.com"
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
  type="Venusberg Campus 1, 53127 Bonn"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Under construction"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Under construction"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Under construction
{% endcapture %}

{% capture col2 %}
Under construction
{% endcapture %}

{% capture col3 %}
Under construction
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
