---
layout: default
title: Teaching
permalink: /teaching/
weight: 2
group: teaching
---
I taught BADM 313, Strategic Human Resource Management in Fall 2021 (17-week course). My mid-term rating as an instructor was 4.25 and I thoroughly enjoyed class discussions with the students.

{% for course in site.data.courses %}
<div class="row" name="{{ course.id }}">
  <div class="row-pic">
		{% include /functions/getcoursepic.html course=course %}
	</div>
	<div class="row-info">
    <a href="{{ course.website | default: "#" }}" target="_blank">{{ course.id }} {{ course.name }}</a>
		<p>
      {{ course.description }}
    </p>
	</div>
</div>

I have also been a **Teaching Assistant** for the following courses: 
* *Leading and Managing Purpose-Driven Organizations* for Prof. Willie Ocasio in Spring 2021
             
* *Leadership and Teams* for Prof. Matthew Kraatz in Fall 2020
{% endfor %}
