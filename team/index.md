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

## Postdoc Researchers

{% include list.html data="members" component="portrait" filters="role: postdoc" %}

{% include section.html %}

## PhD Students

{% include list.html data="members" component="portrait" filters="role: phd" sort_by="grade" %}

{% include section.html %}

## Undergraduate Students

{% include list.html data="members" component="portrait" filters="role: undergrad" sort_by="grade" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portraitalumni" filters="role: alumni" %}
