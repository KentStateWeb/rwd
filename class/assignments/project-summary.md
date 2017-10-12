---
title: "Semester Project Overview"
description: "See an overview of the semester project."
layout: wide
---

## The Setup

* You're an employee at a small web design shop and have just gotten one of your first clients - a small website project for their business.
* Your boss has assigned you (and maybe a coworker) to the project.  You are both equally responsible for development, design and content strategy.
* The client is launching their business in a few months, so they need most of the design/development done and approved before then.
* They plan to put the site into a content management system - but they need a working style guide and prototype in order to effectively implement it.
* They have an onsite employee who will be maintaining and improving the website after the project is finished.

*Note: In this scenario, I will play the client and the business, while based on some actual businesses, will be fictional*

## Project Goals

Why this type of project?  This allows you, the student, to apply what you're learning in class to a real-world scenario.  By thinking critically and using these principles, you're developing long-lasting development and design skills that can be used to land you a job or complement your existing areas of expertise.

## Project Groups

You'll work in pairs on this project.  Each pair will work on a slightly different (but largely equivalent) web project.  The projects are as follows:

{% assign items = site.groups | sort: "number" %}
<ul>
{% for item in items %}
	{% if item.semester == 'fall-2017' %}
	<li><a href="{{ item.url }}">{{ item.title }}: {{ item.client}} ({{ item.members }})</a></li>
	{% endif %}
{% endfor %}
</ul>

## Project Schedule

You and your boss have worked together to develop a brief project schedule.


### 1: Research

* Meet with the client and determine project goals, design aesthetic, etc.
* Communicate why investing in a responsive website makes sense for their business.
* Understand the types of content needed
* Communicate the project schedule
* Get a list of competitors in preparation for doing a brief competitive analysis.
* Put together a project in GitHub that will house all future project deliverables so that they're easy to access by the client.

<a class="button small" href="/class/assignments/research">View Research Project</a>

###  2: Content, Architecture and Sketching

* Collect any existing content that the client has provided
* Reformat and rewrite that content using a mobile-first methodology
* Ask the client for any missing content
* Put together a sitemap in Google Docs
* Based on your content, you'll develop a few, mobile-first sketches to show the client
* The sketches will show some of the main templates that you'll be developing.  You may choose to show them at different breakpoints.
* Using the sketches, you'll identify the repeatable patterns present in your design

<a class="button small" href="/class/assignments/content">View Content Project</a>

###  3:  Style Tiles, Prototype and Concepts

* Using the goals you discovered in your client meeting, you'll develop 2 sets of style tiles that show the colors, design aesthetic and personality of the website.
* You'll show these to the "client" in class, and the class will ask questions.
* From the style tile feedback, you'll develop a few visual mockups representing different screen sizes.

<a class="button small" href="/class/assignments/style">View Style Project</a>

###  4:  Basic Wireframes and HTML/CSS Final Patterns/Prototype/Templates

This piece includes Basic Wireframes, Patterns 1 and 2 and Final Templates/Pattern Library.  You'll submit project updates each week, but won't actually submit this part until the end.

* You'll begin putting together the content you gathered into an HTML template structure
* You'll prioritize the most important content up top
* The content wireframes will demonstrate to the client how the site will respond at different breakpoints.
* Using your content templates, you'll begin to add CSS styling to your code, creating working prototypes of representative templates in your website.
* You'll determine how each repeatable element looks and functions together
* Based on your final prototypes, you'll develop a pattern library that demonstrates the typography, colors and primary atomic elements used in the design

<a class="button small" href="/class/assignments/templates">View Template Project</a>

###  5:  Technical, Accessibility and Usability Testing

* You'll prepare a testing plan for your prototypes, having some real users perform some simple tasks
* You'll see how the site renders on different browsers and devices, and make adjustments.
* You'll run performance tests to see how you can optimize and improve your prototype

<a class="button small" href="/class/assignments/testing">View Testing Project</a>

### 6:  Project Hub, Review Session & Critiques

* You'll invite the client in for a hands-on walkthrough of the final prototype and style guide
* You'll show a retrospective of what you did to get to this point via the Project Hub
* The class will participate, asking questions and making suggestions
* The class will evaluate the success of your design based on the client's initial goals

<a class="button small" href="/class/assignments/timeline-presentation">View Project Hub/Review Session Project</a>

### 7:  Group and Self Assessment

* Your boss wants to know how you think the project went and what you could do better.
* You'll evaluate yourself and your team member (if applicable)

<a class="button small" href="/class/assignments/">View Group/Self Assessment Project</a>
