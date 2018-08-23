---
title: "CSS Grids"
description: "Description of the assignment"
type: "challenge"
points: 6
layout: assignment
date: 2018-11-07 12:00:00
semester: fall-2018
#status: assignment-completed

---

## Introduction

[The Great Race](http://www.rungreatrace.com) is held yearly in Pittsburgh.  The race organizers have come to you because they're really unhappy with their outdated website, but they don't have a lot of time or budget for a redesign.

Their chief complaint is that the website isn't responsive!  Many people use the website from their phones to register for the race and check race results.

They'd like to do a full redesign in the future, but in the interim, they'd like to "retrofit" the website's home page into a responsive one.  

<a href="http://www.rungreatrace.com" class="button small">View Current Site</a>


## What To Do

In CodePen, you're going to translate the existing desktop-only website into a responsive one using the existing assets and content available on the website.  

You and the client have already worked on a sketch of how you think the content might be laid out on the responsive version.

<a class="button small" href="/files/greatrace-sketch.pdf">View Sketch</a>

### Body and Global Elements

The site uses a standard sans-serif font and has a [background-image](http://www.rungreatrace.com/images/backgroundanew.png) and blue background color (#006699).

### Header and Navigation

The header is made up currently of a line of text within an image, which could be more easily translated to text.  

The navigation is a list of items.  You do not have to create the "drop-down" menus (just the parent level items), as we haven't learned this functionality quite yet.

### Body Area

Consists of 2 images, the [logo](http://www.rungreatrace.com/images/homelogo.png) and a photo ([better photo](http://www.post-gazette.com/image/2017/09/17/1140x_q90_a10-7_cTC_ca0,0,2040,1167/Next0917-RaceStart.jpg)).  You can just use a static image, as we haven't learned about slideshows yet.

There are 3 additional link sections below the images.  You should use either flexbox or grid here to accomplish this.

### Footer

Includes 3 logos, a row of social icons and a promotional tile for a video.  You should use either flexbox or grid here to accomplish this.

Also includes contact information and a hotline phone number.


### Assets and Colors

CodePen won't allow you to upload images and assets, so I've provided the links below.

You may also need to use the web inspector to see how the page is built now.

#### Colors

* Dark Blue: #006699
* Gold: #FFCC00
* Green: #CCFF00

#### Assets

* Title (this could also be converted to text) - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/title.png
* Logo - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/homelogo.png
* Sponsor tile - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/logo_eatnpark.gif
* Results Burst - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/burst-ov.png
* Facebook - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/icons-tmp.png
* Instagram - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/instagram.png
* Twitter - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/twitter.png
* Background Image - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/backgroundanew.png
* Main Feature Photo - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/Next0917-RaceStart.jpg
* Additional Sponsor Logos - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/icons.png
* Video Highlights - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/videopromo.png
* Background Gradient - https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/grade.png (you could probably also just do this with a CSS gradient)

## How You'll Be Graded

This is an open-ended assignment, meaning I have no specific expectations for the final design/look and feel, except:

1.  Your assignment is marked up in proper HTML, using the correct elements as needed.
2.  Your CSS is formatted properly with media queries starting at a small screen and then changing to a large screen.
3.  You've used flexbox or grid to position items side-by-side in appropriate places.
4.  The design effectively replicates the original website design, with design changes as appropriate to create the responsive site.  

---

### Submitting the Assignment

1. Once you're satisfied, copy the Editor Mode URL from CodePen
2. Log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste the URL of the Pen (Editor Mode).  Click Submit.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **5 - 6**: HTML CSS and accompanying media queries is written appropriately.  All steps were followed and correct styles are applied.  The design mostly mirrors the original, with proper steps taken for responsive format.  You used either flexbox or grid to position elements.
* **3 - 4**: CSS is mostly structured correctly, but there are some syntax and/or media query issues (for example, you forgot to close a rule with a semicolon).  Some of the steps were missed.  The design doesn't work well at some responsive breakpoints.
* **0 - 2**: CSS does not use appropriate style attributes.  Media queries are not set correctly.  Syntax is incorrect and many of the steps were missed.  The layout isn't appropriate for a responsive website.
