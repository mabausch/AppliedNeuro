---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Contribute to our lab's mission to explore the frontiers of epilepsy and memory neuroscience, employing neurotechnologies in both clinical settings and the field. We're looking for motivated individuals to join our interdisciplinary team, focused on innovative research. Start your journey with us and discover the impact you can make.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi1" %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
