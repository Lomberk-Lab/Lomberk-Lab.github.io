---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team focuses on epigenetic mechanisms that drive pancreatic cancer by combining molecular biology and computational approaches. We leverage these insights to develop and test targeted experimental therapeutics. 

Our laboratory is actively recruiting for a Research Technician as well as graduate students who take pride in rigorous science and is eager to develop their skills within a collaborative, discovery-driven research environment. Please inquire with Dr. Gwen Lomberk if you are interested in joining our team!

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
