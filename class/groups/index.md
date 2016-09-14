---
layout: wide
title: Groups & Projects
---

<a href="/class" class="button small">Return to Class</a>

<p>You can learn more about the semester project in general by reading the <a href="/class/assignments/project-summary.html">Project Summary</a>.</p>

## Initial Group Members ##


Group 7 (Still Needs Client):
Nico Ciani
Nicole Albright

## Groups + Projects ##

<ul>
{% for groups in site.groups | sort: "number" %}
	{% if groups.semester == 'fall-2016' %}
	  {% include groups.html %}
	{% endif %}
{% endfor %}
</ul>

<h2>Group Work Rules & Expectations</h2>

<p>This class uses team-based learning for part or all of the semester.</p>

<a href="policies" class="button small">View Group Rules & Expectations</a>
