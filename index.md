---
layout: default
title: Research
weight: 1
group: research
---

I am a doctoral student of Organizational Theory in Business Administration at the Gies College of Business, University of Illinois at Urbana-Champaign. I am currently in my fourth year of graduate studies. My research interests and active projects are three-fold: (a) organizational culture and it's influence on institutions (b) Innovation Ecosystems and (c) Digital Governance of AI and Big Data

Below is a list of my current and inactive projects.

### Current Projects
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

### Inactive Projects
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %}
{% include projects.html data=inactive %}
