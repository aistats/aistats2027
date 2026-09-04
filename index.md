---
title: Home
layout: default
weight: 1
---

The {{ site.conference.instance }} {{ site.conference.styling }} {{ site.conference.full_name }} ({{ site.conference.short_name }}) will be held in {{ site.conference.year }}{% if site.conference.location %} in {{ site.conference.location }}{% endif %}{% if site.conference.venue %} at {{ site.conference.venue }}{% endif %}.

Meeting dates and venue details will be announced when confirmed. 

{% if site.author.email %}
General inquiries should be sent to [{{ site.author.email }}](mailto:{{ site.author.email }}).
{% endif %}
