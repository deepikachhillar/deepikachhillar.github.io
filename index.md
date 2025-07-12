---
layout: default
title: Research
weight: 1
group: research
---

I am an incoming Assistant Professor of Management at the Daniels College of Business, University of Denver. My research sits at the intersection of strategic human resource management, sustainability, and digital governance. I hold a Ph.D. in Business Administration from the Gies College of Business, University of Illinois Urbana-Champaign, and dual degrees in Economics and Computer Science Engineering from BITS Pilani, India.

Prior to academia, I worked across firms in roles spanning leadership development, advanced analytics, and market risk. 

Below is a list of academic work that reflects my ongoing research agenda, including peer-reviewed publications, and works in progress.

### Published Articles
{% assign inactive = site.data.projects | where_exp: "project", "project.end == 2022" %} {% include projects.html data=inactive %}

### Manuscripts under Review
{% assign current = site.data.projects | where_exp: "project", "project.end == 2023" %}
{% include projects.html data=current %}

### Working Papers
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

### Selected Work in Progress
{% assign current = site.data.projects | where_exp: "project", "project.start == 2023" %}
{% include projects.html data=current %}
