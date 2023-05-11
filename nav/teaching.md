---
layout: default
title: Teaching
permalink: /teaching/
weight: 2
group: teaching
---


I taught BADM 313, Strategic Human Resource Management in Fall 2021 (17-week course). My final average rating was 4.37. I thoroughly enjoyed teaching this course and looks like the students did as well:
![image](https://github.com/deepikachhillar/deepikachhillar.github.io/assets/58666758/9f2cf8e7-0930-498d-a5a6-b11aa270d573)

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

<figure>
	<img style="display=inline" width="40%" src="{{ "/resources/images/courses/IMG_3923.png" |  prepend: site.baseurl }}" alt="Class Picture" />
</figure>

Here is an attempt to capture a memory of my first-cohort of students.
<figure>
	<img style="display=inline" width="60%" src="{{ "/resources/images/courses/IMG_3911.png" |  prepend: site.baseurl }}" alt="Class Picture" />
</figure>

*" She did an amazing job with preparation and filled each class with perfect amount of content. I loved all the connections made to real life events from 2021 as it added immersion."\
" I enjoyed this instructor a great deal, she was awesome and always offered great instruction and feedback."\
" Deepika was very passionate about course content and seemed to have extensive knowledge on the topics. This made asking questions comfortable and always warranted an elaborate response."*\
And yet the best one was... *" She really cares."*.

