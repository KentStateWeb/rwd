---
title: "HTML/CSS Pattern Library"
description: "Description of the assignment"
type: "project"
points: 5
layout: assignment
date: 2016-12-13 11:59:00
semester: fall-2016
---

You've been developing your sites' templates using a variety of components that make up the website as a whole.  Lets take a step back and document the primary elements and styles used in your website.  

Why create a pattern library? We need to communicate our design choices to anyone else who may be managing or editing the site once we're gone.  A pattern library serves as a great reference for your client or other developers who want to look up fonts, color values, or code examples.

Pattern Libraries can be very simple or very complex (see MailChimp).  They may also include a style guide component, which discusses things like voice & tone, messaging, etc.  We're going to keep ours simple.

## What To Do

It's helpful to view our site both as a whole and also via its atomic components/patterns (as we learned when studying Brad Frost's Atomic Design methodology).  The components that make up your site can be repeated across many different templates for consistency.  A component might be as simple as a heading, or as complex as a header or primary navigation.

1.  Identify 5 common patterns that make up your website.  These could be generic patterns, like headers, headings, paragraphs, lists, or patterns that are specific to your website, like product description, shopping cart, etc.

2.  Create a new directory in your repository and call it "patterns".  Create a new index.html in the patterns folder.  You can use the HTML code below to fill in the default HTML header code.

3.  You could create a separate styles.css.  However, since you already have a working stylesheet in your templates folder, you can instead change the link tag to reference the existing stylesheet (in the templates folder).  Hint: it will probably be: link href="../templates/style.css" rel="stylesheet" type="text/css" media="screen"

4.  Add a heading titled Pattern Library.

5.  Copy the code for your 5 patterns onto your pattern library, each separated with a heading.

6.  Under typography, document the fonts used on your website.

7.  Under colors, document the colors used on your website.  You might display these in the actual colors.

### View an Example

You can <a href="http://rwdkent.com/patterns/">view the pattern library for the RWD Kent State site</a> to see an example.

### Adding HTML + Stylesheet

<script src="https://gist.github.com/challahan/08eddc8da7152f483f99.js"></script>

## How to Turn In the Assignment

You'll be submitting your pattern library via your GitHub repository.

1.  Make sure your pattern library is added to a folder named "patterns"
2.  On your root index.html file, which is the Project Hub, add an H2 with Date: Pattern Library.
3.  Add a link to your pattern library under the Pattern Library section.
4.  After you've commited and synced your changes via GitHub Desktop, you can submit both the timeline hyperlink and the link to your pattern library.  Note: Don't link to the local version on your computer.  You need to access the live version on the web with the GitHub.io URL.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **4-5**: Your pattern library uses existing components from your templates (at least 5) and they are adequately demonstrated on a single page.  You've also documented the colors and fonts that you're using on your site.  Finally, you've submitted the pattern library according to directions.
* **2-3**: You're missing some core components from your website.  You may have forgotten to document colors or typography.
* **0-1**: Your pattern library poorly demonstrates the components used in your website.  HTML code may not be formatted correctly.
