---
title: Home
layout: default
weight: 1
---

The {{ site.conference.instance }} {{ site.conference.styling }} {{ site.conference.full_name }} ({{ site.conference.short_name }}) will be held in {{ site.conference.year }}{% if site.conference.location %} in **{{ site.conference.location }}**{% endif %}{% if site.conference.venue %} at {{ site.conference.venue }}{% endif %}.

AISTATS is an interdisciplinary gathering of researchers at the intersection of artificial intelligence, machine learning, statistics, and related areas. The conference provides a forum for presenting and discussing new research in these fields. The conference invites submissions of original research, which are peer-reviewed, with accepted papers published in the archival Proceedings of Machine Learning Research (PMLR) series.

In addition to the main conference program, **AISTATS 2027 will, for the second time, feature a dedicated workshop day**, providing a forum for focused discussion of emerging topics and research directions.

For AISTATS 2027, the [virtual conference website](https://virtual.aistats.org/Conferences/2027) will serve as the primary source for up-to-date conference information and communication, including announcements and information for participants. This website provides general and archival information about the conference.

{% if site.author.email %}
General inquiries should be sent to [{{ site.author.email }}](mailto:{{ site.author.email }}).
{% endif %}