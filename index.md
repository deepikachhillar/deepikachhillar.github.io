---
layout: default
title: Research
weight: 1
group: research
---

I am a doctoral candidate in the **Organizational Theory & Strategy** area at the [Gies School of Business](https://giesbusiness.illinois.edu/){:target="_blank"}, **University of Illinois, Urbana-Champaign**. 

I am a management scholar who examines the competing organizational demands between financial performance and social responsibility using computational science. My current work focuses on **organizational purpose** and **culture** whereby I analyze textual data from [Glassdoor](https://www.glassdoor.com/member/home/index.htm){:target="_blank}.

Below is a list of my published articles and current projects.

### Published Articles
{% assign inactive = site.data.projects | where_exp: "project", "project.end == 2022" %} {% include projects.html data=inactive %}

### Manuscripts under Review
{% assign current = site.data.projects | where_exp: "project", "project.end == 2023" %}
{% include projects.html data=current %}

### Working Papers
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}
