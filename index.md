---
layout: home
title: Agenda
---

# Chips & Compilers Symposium at MLSys'21

The rapid advance in ML models and ML-specific hardware makes it increasingly challenging to build efficient and scalable learning systems that can take full advantage of modern hardware and runtime environments' performance capability. We need to make full use of hardware specialization and compilation techniques to provide the best performance for modern machine learning workloads.

This symposium aims to bring together experts from the field of computer architecture and compilers. The list of invited speakers contains experts across the compilation and hardware stack.



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
