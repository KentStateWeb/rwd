---
layout: wide
title: Groups & Projects
---

<a href="/class" class="button small">Return to Class</a>

<p>You can learn more about the semester project in general by reading the <a href="/class/assignments/project-summary.html">Project Summary</a>.</p>

## Initial Group Members ##

Group 1:
Kierstynn Lund
Joshua Graef

Group 2:
Tyler Cronie
Lauren Rhinehalt

Group 3:
Courtney Klesta
Dorothy Ly

Group 4:
Lauren Friedman
Lindsey Meisterheim

Group 5:
Samantha Hudak
Cory Sutter

Group 6:
Julia Holmberg
Laura Mamick

Group 7:
Nico
Derek

Group 8:
Grant Wang
Nicole Albright

Group 9:
Khan Van Le
Brenan Strutter

## Groups + Projects ##

<ul>
{% for groups in site.groups | sort: 'description' %}
	{% if groups.semester == 'fall-2016' %}
	  {% include groups.html %}
	{% endif %}
{% endfor %}
</ul>

<h2>Group Work Rules & Expectations</h2>

<p>This class uses team-based learning for part or all of the semester.</p>

<a href="policies" class="button small">View Group Rules & Expectations</a>
