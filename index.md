---
layout: home
title: Agenda
---

# Chips & Compilers Symposium at MLSys'21




Efficient and scalable learning systems need to take full advantage of modern hardware and runtime environments' performance capability. 
The rapid advance in ML models and ML-specific hardware makes this task increasingly challenging. 
This symposium aims to bring together experts from the field of computer architecture and compilers, to discuss about ML-specific hardware, and how to fully use hardware specialization and compilation techniques to provide the best performance for modern machine learning workloads.



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
