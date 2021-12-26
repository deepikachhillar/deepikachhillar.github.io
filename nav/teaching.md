---
layout: default
title: Teaching
permalink: /teaching/
weight: 2
group: teaching
---
I taught BADM 313, Strategic Human Resource Management in Fall 2021. My mid-term rating was 4.25 and I thoroughly enjoyed my discussions with the students. 
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
{% endfor %}
