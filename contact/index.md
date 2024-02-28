---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Under Construction.

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
