---
layout: default
title: Research
weight: 1
group: research
---

I am a doctoral student of Organizational Theory and Strategy in Business Administration at the Gies College of Business, University of Illinois at Urbana-Champaign. I am currently in my fourth year of graduate studies. My research interests are three-fold: (a) Organizational Culture (b) Governance of AI and Big Data and (c) Innovation Ecosystems

Below is a list of my current and inactive projects.

### Current Projects
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

### Inactive Projects
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %}
{% include projects.html data=inactive %}
