---
layout: default
title: Research
weight: 1
group: research
---

I am a computational social scientist and a management scholar at the [Gies School of Business](https://giesbusiness.illinois.edu/){:target="_blank"}, University of Illinois, Urbana-Champaign.

I use computational methods to examine how firms balance competing organizational demands of financial performance and social responsibility. My dissertation work focuses on **purpose** and **culture**. Below is a list of my published articles and current projects.

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
