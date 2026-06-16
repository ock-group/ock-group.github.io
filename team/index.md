---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

## Principal Investigator

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include section.html %}

## Graduate Students

{% include list.html data="members" component="portrait" filter="role != 'pi' && role != 'undergrad' && group == 'team'" %}

{% include section.html %}

## Undergraduate Researchers

{% include list.html data="members" component="portrait" filter="role == 'undergrad' && group == 'team'" %}

{% include section.html %}



{% include section.html %}

## Alumni

{% include list.html  data="members"  component="portrait"  filter="group == 'alumni'" %}

{% include section.html %}
