---
layout: page
permalink: /papers-club/
title: papers club
description: papers we read, grouped by theme.
nav: true
nav_order: 3
toc:
  sidebar: left
---

A running list of papers for discussion. New categories can be added next to the fundamentals.

{% for category in site.data.papers_club.categories %}

## {{ category.name }}

{{ category.description }}

{% for paper in category.papers %}
- **{{ paper.short }}.** [{{ paper.title }}]({{ paper.url }})  
  {{ paper.authors }}. *{{ paper.venue }}*, {{ paper.year }}.
{% endfor %}

{% endfor %}
