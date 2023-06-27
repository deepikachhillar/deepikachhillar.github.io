---
layout: default
title: Research
weight: 1
group: research
---


![image](https://github.com/deepikachhillar/deepikachhillar.github.io/assets/58666758/e3322f55-73b7-4a05-ac84-1ca794080b8b)
I am a doctoral candidate in the **Organizational Theory & Strategy** area at the [Gies School of Business](https://giesbusiness.illinois.edu/){:target="_blank"}, **University of Illinois, Urbana-Champaign**.

My main research stream examines how organizations can become socially responsible towards their stakeholders, especially as they navigate the demands of existential modernism and upholding ethics. I draw on theoretical traditions in organizational theory, strategic management, and artificial intelligence. Across the breadth of my research, I seek to address existential concerns about humanistic futures for organizations and the economy. These concerns relate to the potential diminishing importance of human-centered values, principles, and aspirations in the context of organizational and economic systems. I draw from a toolkit of computational and quantitative methods and hope to contribute to the field through the spirit of engaged scholarship.

Below is a list of my published articles and current projects.

### Published Articles
{% assign inactive = site.data.projects | where_exp: "project", "project.end == 2022" %} {% include projects.html data=inactive %}

### Manuscripts under Review
{% assign current = site.data.projects | where_exp: "project", "project.end == 2023" %}
{% include projects.html data=current %}

### Working Papers
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}
