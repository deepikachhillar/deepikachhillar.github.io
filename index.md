---
layout: default
title: Research
weight: 1
group: research
---

I am a doctoral candidate in the **Organizational Theory & Strategy** area at the Gies School of Business at the University of Illinois, Urbana-Champaign. I will be on the **2023-24 academic job market**. 

I completed my Masters in Economics and BE in Computer Science from BITS Pilani. My research interests include understanding and enhancing the cultural life of organizations, studying technological discontinuities, and the governing role of institutions. My work employs a variety of computational methods, including natural language processing, and machine learning.

Below is a list of my published articles and current projects.

### Published Articles
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %} {% include projects.html data=inactive %}

### Working Papers
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}
