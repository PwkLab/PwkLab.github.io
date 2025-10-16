---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'Associate Research Professor'" %}
{% include list.html data="members" component="portrait" filter="role == 'Postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' or role == 'PhD student' or role== \"Master's student\"" %}
{% include list.html data="members" component="portrait" filter="role == 'Lab assistant'" %}
{% include list.html data="members" component="portrait" filter="role == 'Visiting student'" %}



{% include section.html background="images/background.jpg" dark=true %}


{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
