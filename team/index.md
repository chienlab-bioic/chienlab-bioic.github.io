---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Our PI!

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include section.html %}

## PhD Students

{% include list.html data="members" component="portrait" filters="role: phd" %}

{% include section.html %}

## MS Students

{% include list.html data="members" component="portrait" filters="role: ms" %}

{% include section.html %}

## Undergraduate Students

{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: alumni" %}
