---
layout: default
title: Service
navtitle: Service
permalink: /service/
weight: 5
group: service
---

{% assign thisYear = "now" | date: "%Y" | plus: 0 %}

{% assign current = site.data.services | where_exp: "service", "service.year >= 2019"%}
{% assign past = site.data.services | where_exp: "service", "service.year < 2020"%}

 
### Current
{% include services.html data=current %}

### Past
{% include services.html data=past %}

