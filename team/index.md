---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our laboratory is actively recruiting for a Research Technician as well as graduate students who take pride in rigorous science and are eager to develop their skills within a collaborative, discovery-driven research environment. Please inquire with Dr. Gwen Lomberk if you are interested in joining our team!

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-photo-film" %}Lab Photos

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
