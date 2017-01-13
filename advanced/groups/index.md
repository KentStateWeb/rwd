---
layout: wide
title: Advanced RWD Groups
---

<a href="/advanced" class="button small">Return to Class</a>

Officially, Scrum recognizes no specific roles or titles for development team members.  This ensures there are no barriers to collaboration - everyone is equally responsible for the end result.  

However, being a classroom team that does not meet 5 days a week, I am going to structure the development team into lightweight roles to help distinguish responsibilities and roles throughout the project.  

You may, with the permission of the instructor, choose to trade roles with another team member at the beginning of a sprint, if needed.  


## Subgroups ##

{% assign items = site.groups_arwd | sort: "number" %}

<section>
{% for item in items %}
	{% if item.semester == 'spring-2017' %}
		<h3>{{ item.title }}</h3>
		<dl>
		<dt>Members</dt>
		<dd>{{ item.members }}</dd>
		</dl>
		<p>{{ item.description }}</p>
	{% endif %}
{% endfor %}
</section>
<br/>

<h2>Group Work Rules & Expectations</h2>

<p>This class uses team-based learning for part or all of the semester.</p>

<a href="policies" class="button small">View Group Rules & Expectations</a>
