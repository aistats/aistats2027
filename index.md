---
title: Home
layout: default
weight: 1
---

The {{ site.conference.instance }} {{ site.conference.styling }} {{ site.conference.full_name }} ({{ site.conference.short_name }}) will be held in {{ site.conference.year }}{% if site.conference.location %} in {{ site.conference.location }}{% endif %}{% if site.conference.venue %} at {{ site.conference.venue }}{% endif %}.

This site is maintained in parallel with the [virtual AISTATS 2027 website](https://virtual.aistats.org/Conferences/2027).

{% if site.author.email %}
General inquiries should be sent to [{{ site.author.email }}](mailto:{{ site.author.email }}).
{% endif %}
