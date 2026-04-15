---
title: Contact
nav:
  order: 5
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

For any research-related inquires please reach out to Dr. Gwen Lomberk via the link below.

{%
  include button.html
  type="email"
  link="lomberk.gwen@mayo.edu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}
