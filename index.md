---
layout: home
title: Agenda
---

# Chips & Compilers Symposium at MLSys'21


## Speakers

{% assign speakers = site.staffers | where: 'role', 'Speaker' %}
{% for staffer in speakers %}
{{ staffer }}
{% endfor %}

<div style="clear: both;"></div>

## Organizers

{% assign organizers = site.staffers | where: 'role', 'Organizer' %}
{% for staffer in organizers %}
{{ staffer }}
{% endfor %}

<div style="clear: both;"></div>

## Agenda

{% for module in site.modules %}
{{ module }}
{% endfor %}
