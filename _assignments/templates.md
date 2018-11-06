---
title: "HTML/CSS Templates/Patterns"
description: "We're now on our way to making a real, functioning website."
type: "project"
points: 15
layout: assignment
date: 2018-12-12 11:00:00
semester: fall-2018
---

We're now on our way to making a real, functioning website.  For the purposes of this project, we will be producing three prototype templates that would eventually become the website.  Using these three templates, we would easily be able to do produce the rest of the site.

Instead of producing all of the templates at once, we'll split this assignment into 5 parts over the last part of the semester.

1.  <a href="#1">Basic Wireframe Structure and Mockups: Week 12</a>
2.  <a href="#2">Patterns - Global: Week 13</a>
3.  <a href="#3">Patterns - Page Level: Week 14</a>
4.  <a href="#4">Combined Templates and Patterns - Instructor Review: Week 15</a>
5.  <a href="#5">Final Templates and Patterns: Finals Week</a>

---

<span id="1"></span>

## Part 1: Basic HTML Wireframes

You've already sketched out your site on paper and developed a lot of the core content.  Now we need to start developing your content into HTML wireframes.  The wireframes will be built mobile-first and demonstrate the content priority in each of your 3 templates.

Remember, the wireframes don't need to be "pretty" yet.  We're going to create the structure first, and then slowly add style and layout (including responsive breakpoints) to our templates through CSS.

### What To Do

1.  Create a new folder in your project repository and call it "prototype".  
2.  Inside the folder, create three individual HTML files.  One is going to be called index.html (which will be your home page template).  The other two are your choice, depending on which 2 other templates are most important for your website.  For example, a Product page might be considered a template.  You don't have to create a separate template for each Product, since they will all follow the same basic format.
3. Create a structure for each of the HTML pages, based on your content.  Most of your sites will include the global header and footer patterns.  The rest of the content elements are up to you.
4. Use semantic HTML to mark up your content.  For example, you might surround your main content using the MAIN HTML template and the header using the HEADER tag. If your site uses navigation, mark it up using an unordered list.  We'll everything in the next assignments.
5. Add real content into your 3 templates.  The content should be representative of the actual content that will be on the website, not lorem ipsum.  Links don't necessary need to work right now.
6. Once you have created your three templates, create a new file called "style.css".  This is where your styles will eventually go.
7. Link your stylesheet to each of your main templates, using the code below.
8. Add a few default styles to make your templates a bit easier to view.  Use the starter CSS below.

### Starter HTML Code with Stylesheet Link

<script src="https://gist.github.com/challahan/08eddc8da7152f483f99.js"></script>

### Starter CSS Code for Wireframing

These styles will help give outlines to your elements.  You'll delete them eventually.

<script src="https://gist.github.com/challahan/8d1a513d126feb7e69ce.js"></script>

### Wireframe Example

Your wireframes might look something like <a href="http://rwdkent.com/wireframes/index.html">these wireframes, used to create the RWD website</a>.

---

<span id="2"></span>

## Part 2: Prototype Patterns - Global

### What To Do

Rather than styling everything at once, this week we're going to pick out "global" patterns to style first on your templates.

What do we mean by global?  These are design pieces that are shared among most or every page on the website.  This commonly includes:

* Header and Logo
* Primary Navigation
* Footer
* Heading Styles (1 - 6)
* Paragraph Styles
* Buttons
* Ordered/Unordered List Styles
* Sidebar/Secondary Navigation
* Main Content Area (Container that holds the main content) and Background

Using the stylesheet you've already created and your 3 "wireframe" templates, focus on styling these components for this week.  You will review these with both the instructor and class.  

---

<span id="3"></span>

## Part 3: Prototype Patterns - Page Level Components

For this week, we're going to dive into the specific components that make up the core of each page or template.  These might be considered molecules or organisms in atomic design.  

Specific page-level components could include:

1.  A hero image or slider
2.  A food menu item
3.  An embedded video or map
4.  A calendar or event item
5.  A news story or blog post
6.  Promo blocks/photos

These will vary depending on what components make up your individual templates.

Focus on styling and adding any appropriate JavaScript for these patterns for this week, adding on to the stylesheet you've already created.  You will review these with both the instructor and class.  

---

<span id="4"></span>

## Part 4: Combined Templates and Patterns: Instructor Review

For this week, take both the global patterns and components that you've already developed and refine them into a cohesive, working design.  

The instructor will individually review these templates with you and give feedback.

You'll also use these for usability, accessibility and technical testing, so they have to be functional and working.

After this week, you'll have one week left to refine them.

---

<span id="5"></span>

## Part 5: Final Templates and Patterns

The finalized working templates (including the feedback you've received so far) are due in class today.  You'll demonstrate them along with your Project Hub and Pattern Lab in the <a href="http://rwd.web/class/assignments/timeline-presentation/">Review Session"</a> during finals week.

---

## How to Turn In the Assignment

You'll be submitting your templates via your GitHub repository.  You'll simply update the same files each week as you progress.  

1.  Make sure your three templates are placed in the "templates" folder
2.  On your root index.html file, which is the Project Hub, add an H2 with Date: Templates.
3.  Add a link to your three templates under the Templates section.  Name each link with the title of the template, for example "Product Page Template".
4.  After you've committed and synced your changes via GitHub Desktop, you can submit both the timeline hyperlink and the link your three templates via Blackboard Learn.  Note: Don't link to the local version on your computer.  You need to access the live version on the web with the GitHub.io URL.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **10-15**: You've put everything you've learned so far together.  Your templates' HTML and CSS uses the appropriate content and styles.  Your templates form a cohesive whole, but also demonstrate a unified design system.  Your HTML is structured well, and you are using appropriate breakpoints in your CSS. Your website renders correctly on popular phones, tablets and desktop computers. You demonstrated weekly progress and stayed on task for each of the 5 parts.
* **5-9**: You've put together the templates, but they don't always show a unified design system.  Some of the content is missing or not in appropriate places.  There are some issues with the responsive breakpoints - more testing may be needed on different sized screens or devices.  There are also a few HTML and CSS errors.  You showed progress most weeks, but may have fallen behind on some parts.
* **0 - 4**: The design system for your templates is week and templates don't follow the structure of your content.  HTML and CSS structure is weak and doesn't follow what you've learned in class.   A lot more work is required to make the templates ready for client review.  You waited until the last minute and didn't have templates/patterns available for class review.
