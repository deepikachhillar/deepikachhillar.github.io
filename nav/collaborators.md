---
layout: default
title: Collaborators
permalink: /collaborators/
weight: 2
group: students
---


<!-- #Maplers are members of my research lab (Maple), including master's and doctoral students, as well as undergrad research assistants. I'm always looking for new students (on all levels) to expand my group.

#If you are interested in joining Maple, I strongly encourage you to apply to the [Computing Science Department at UAlberta](https://www.ualberta.ca/computing-science/graduate-studies/programs-and-admissions/applications-and-admissions). If you'd like to email me regarding joining Maple, please make sure to include the following information in your email for me to consider it:

#- A one-page summary for your research interests. Ideally, this summary should specify at least one of [my current projects](/) that you find interesting.
#- A one-page summary for one of [my published papers](/papers/) that you find interesting.
#- Any relevant background that you have and may be useful for you to pursue your future research directions.
#- The phrase "Messi is the GOAT". This will just show that you are serious enough about joining Maple to read all the way till the end of the list of instructions.
 -->
Below is a list of current and former research collaborators.

### Current Collaborators
<figure>
	<img style="display=inline-block" width="15%" src="{{ "/resources/images/collaborators/matt_kraatz.png" |  prepend: site.baseurl }}" alt="Matthew Kraatz" />
</figure>
My advisor and my mentor, Prof. Matthew Kraatz is the Merle H. & Virginia Downs Boren Professor at the Gies College of Business at the University of Illinois, Urbana-Champaign. 
Paper 
{% assign current = site.data.maplers | where:"status","current" %}
{% include maplers.html data=current %}

### Former Collaborators
{% assign former = site.data.maplers | where:"status","former" %}
{% include maplers.html data=former %}
