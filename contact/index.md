---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We welcome inquiries about our research, potential collaborations, and graduate student or postdoctoral opportunities. Feel free to reach out to us.

{%
  include button.html
  type="email"
  text="hphuang691290@g.ntu.edu.tw"
  link="hphuang691290@g.ntu.edu.tw"
%}
{%
  include button.html
  type="phone"
  text="(02) 2312-3456 ext. 288787"
  link="+886-2-2312-3456,288787"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/National+Taiwan+University+College+of+Medicine"
%}

{% include section.html dark=true %}

{% capture col1 %}
**Mailing Address**  
Graduate Institute of Medical Genomics and Proteomics  
College of Medicine, National Taiwan University  
No. 1, Sec. 1, Ren-Ai Road  
Taipei 100, Taiwan
{% endcapture %}

{% capture col2 %}
**Office Phone**  
(02) 2312-3456 ext. 288787  
**Lab Phone**  
(02) 2312-3456 ext. 288788
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}