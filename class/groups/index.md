---
layout: wide
title: Groups & Projects
---

<a href="/class" class="button small">Return to Class</a>

<p>You can learn more about the semester project in general by reading the <a href="/class/assignments/project-summary.html">Project Summary</a>.</p>

## Groups + Projects ##

#### Chris Hallahan's Class

{% assign items = site.groups | sort: "number" %}
<ul class="group-list">
{% for item in items %}
	{% if item.semester == 'fall-2018' and item.class == "hallahan" %}
	<li><a href="{{ item.url }}">{{ item.title }}: {{ item.client}} ({{ item.members }})</a></li>
	{% endif %}
{% endfor %}
</ul>


#### Dave Roll's Class

{% assign items = site.groups | sort: "number" %}
<ul class="group-list">
{% for item in items %}
	{% if item.semester == 'fall-2018' and item.class != "hallahan" %}
	<li><a href="{{ item.url }}">{{ item.title }}: {{ item.client}} ({{ item.members }})</a></li>
	{% endif %}
{% endfor %}
</ul>


<h2>Group Work Rules & Expectations</h2>

<p>This class uses team-based learning for part or all of the semester.</p>

<a href="policies" class="button small">View Group Rules & Expectations</a>
