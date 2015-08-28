---
title: "HTML/CSS Pattern Library"
description: "Description of the assignment"
type: "project"
points: 5
layout: assignment
date: 2015-12-08 12:00:00
---

You've been developing your sites' templates using a variety of components that make up the website as a whole.  Lets take a step back and document the primary elements and styles used in your website.  

Why create a pattern library? We need to communicate our design choices to anyone else who may be managing or editing the site once we're gone.  A pattern library serves as a great reference for your client or other developers who want to look up fonts, color values, or code examples.

Pattern Libraries can be very simple or very complex (see MailChimp).  They may also include a style guide component, which discusses things like voice & tone, messaging, etc.  We're going to keep ours simple.

## What To Do

It's helpful to view our site both as a whole and also via its atomic components/patterns (as we learned when studying Brad Frost's Atomic Design methodology).  The components that make up your site can be repeated across many different templates for consistency.  A component might be as simple as a heading, or as complex as a header or primary navigation.

1.  Identify 10 common patterns that make up your website.  These could be generic patterns, like headers, headings, paragraphs, lists, or patterns that are specific to your website, like product description, shopping cart, etc.

2.  Create a new directory in your repository and call it "patterns".  Create a new index.html in the patterns folder.  Add in your header/footer by using Jekyll frontmatter.

3  Add a heading titled Pattern Library.

4.  Copy the code for your 10 patterns onto your pattern library, each separated with a heading.

5.  Under typography, document the fonts used on your website.

6.  Under colors, document the color values (hexcodes or RGB values) used on your website.  You might display these in the actual colors.


## How to Turn In the Assignment

You'll be submitting your pattern library via your GitHub repository.

1.  Make sure your pattern library is added to a folder named "patterns" and has the correct Jekyll frontmatter.
2.  On your root index.html file, which is the Project Hub, add an H2 with Date: Pattern Library.
3.  Add a link to your pattern library under the Pattern Library section.
4.  After you've commited and synced your changes via GitHub Desktop, you can submit both the timeline hyperlink and the link to your pattern library.  Note: Don't link to the local version on your computer.  You need to access the live version on the web with the GitHub.io URL.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **4-5**: Your pattern library uses existing components from your templates (at least 10) and they are adequately demonstrated on a single page.  You've also documented the colors and fonts that you're using on your site.  Finally, you've submitted the pattern library according to directions and its using Jekyll templates, so that you're not repeating code.
* **2-3**: You're missing some core components from your website.  You may have forgotten to document colors or typography.  You've repeated some code that could have been dynamically inserted via Jekyll.
* **0-1**: Your pattern library poorly demonstrates the components used in your website.  HTML code may not be formatted correctly. You may not be using Jekyll to drive your header/footer.