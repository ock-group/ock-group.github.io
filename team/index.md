---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi' && group == 'team'" %}

{% include section.html %}

## Visiting Students

{% include list.html data="members" component="portrait" filter="group == 'visiting'" %}
{% include section.html %}

## External Collaborators 

{% include list.html data="members" component="portrait" filter="group == 'external'" %}
{% include section.html %}

## Alumni

{% include list.html  data="members"  component="portrait"  filter="group == 'alumni'" %}

{% include section.html %}
