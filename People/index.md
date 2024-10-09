---
title: People
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}People

<!-- # Current Lab Members -->
## Directors
{% include list.html data="members" component="portrait" filters="role: Lead" background="white" %}
{% include list.html data="members" component="portrait" filters="role: Co-PI" background="white" %}

## Graduate Students
{% include list.html data="members" component="portrait" filters="role: GA, group:phd" background="white" %}
{% include list.html data="members" component="portrait" filters="role: GA, group:msc" background="white" %}

## Research Assistants
{% include list.html data="members" component="portrait" filters="role: RA, group: Research Technician" background="white" %}
{% include list.html data="members" component="portrait" filters="role: RA, group: Co-op Student" background="white" %}
{% include list.html data="members" component="portrait" filters="role: RA, group: Work-Learn Student" background="white" %}
{% include list.html data="members" component="portrait" filters="role: RA, group: Research Assistant" background="white" %}


<!-- Section for Collaborators -->
## Collaborators
{% include list.html data="members" component="portrait" filters="role: Collaborator" background="white" %}

<!-- Section for Alumni -->
{% include section.html %}
## Previous Members
{% include list.html data="members" component="portrait" filters="role: Al" background="gray"%}
