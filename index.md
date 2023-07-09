---
layout: default
title: Research
weight: 1
group: research
---

I am a doctoral candidate in the **Organizational Theory & Strategy** area at the [Gies School of Business](https://giesbusiness.illinois.edu/){:target="_blank"}, **University of Illinois, Urbana-Champaign**. 

My main research stream in **organizational strategy** examines how organizations can become socially responsible towards their stakeholders, especially as they navigate the demands of existential modernism and upholding ethics. My current work focuses on **organizational purpose** and **culture** whereby I analyze textual data from [Glassdoor](https://www.glassdoor.com/member/home/index.htm){:target="_blank}. I draw on theoretical traditions in organizational theory, strategic management, and computational science. Across the breadth of my research, I seek to address existential concerns about humanistic futures for organizations and the economy. These concerns relate to the potential diminishing importance of human-centered values, principles, and aspirations in the context of organizational and economic systems. I draw from a toolkit of computational and quantitative methods and hope to contribute to the field through the spirit of engaged scholarship.

I completed my Masters in **Economics** and BE in **Computer Science** from [BITS Pilani University, India](https://www.bits-pilani.ac.in/){:target="_blank"}. 

Below is a list of my published articles and current projects.

### Published Articles
{% assign inactive = site.data.projects | where_exp: "project", "project.end == 2022" %} {% include projects.html data=inactive %}

### Manuscripts under Review
{% assign current = site.data.projects | where_exp: "project", "project.end == 2023" %}
{% include projects.html data=current %}

### Working Papers
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}
