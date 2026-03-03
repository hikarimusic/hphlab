---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a group of researchers dedicated to understanding the roles of serine proteases in stem cells and disease, modeling genetic disorders with iPSC technology, and investigating pericyte biology in the tumor microenvironment.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}