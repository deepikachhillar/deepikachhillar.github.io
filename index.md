---
layout: default
title: Research
weight: 1
group: research
---

I am a doctoral candidate in the Organizational Theory & Strategy area at the [Gies School of Business](https://giesbusiness.illinois.edu/){:target="_blank"}, University of Illinois, Urbana-Champaign. 

I use computational science to examine how firms balance competing organizational demands of financial performance and social responsibility. My current work focuses on **organizational purpose** and **culture**. Below is a list of my published articles and current projects.

### Published Articles
{% assign inactive = site.data.projects | where_exp: "project", "project.end == 2022" %} {% include projects.html data=inactive %}

### Manuscripts under Review
{% assign current = site.data.projects | where_exp: "project", "project.end == 2023" %}
{% include projects.html data=current %}

### Working Papers
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}
