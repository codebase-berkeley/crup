---
layout: page
title: Staff
nav_order: 3
description: Meet the CRUP team and instructors.
---

# Staff

## Course Staff Email

{: .important }
> Contact course staff **via Ed** with any questions or concerns. For general inquiries, you can reach us at [crup@codebase.berkeley.edu](mailto:crup@codebase.berkeley.edu).

## Executive Vice Presidents (EdVPs)

{% assign edvps = site.staffers | where: 'role', 'EdVP' %}
{% for staffer in edvps %}
{{ staffer }}
{% endfor %}

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Teaching Assistants

{% assign tas = site.staffers | where: 'role', 'TA' %}
{% for staffer in tas %}
{{ staffer }}
{% endfor %}

## Mentors

{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}
