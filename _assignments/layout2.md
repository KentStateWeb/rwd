---
title: "Layout/Media Queries 2"
description: "Description of the assignment"
type: "mini"
points: 5
layout: assignment
date: 2016-04-05 12:00:00
semester: spring-2016
---

Now that we've added a few breakpoints to our site, we're going to make some more dramatic layout adjustments using floats.  Be sure to reference the part of your book on floats and positioning for this section. 

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

Open your Layout/Media Queries assignment.  Instead of editing the original pen, click the "Fork" option at the top.  Click Settings and rename the forked pen using this structure: "Your Last Name - Layout/Media Queries 2".

### Header 

Heads up - you're going to be doing some complex media queries in this section.  Remember these guidelines:  a. Order your media queries from smallest to largest  b. Organize your CSS by element (for example, header and footer)  and  c. Remember your first media query is no media at all.  These are your default styles.

Your header will start out stacked, and then end up horizontal when the space allows for it.

1.  Set the heading 1 (aka Welcome Weekend) to a smaller font-size to start out, so that the text fits small screens better.  
2. Set the Welcome Weekend logo to start out at a smaller width of around 80px.
3. At around 600px, change the Welcome Weekend logo to be 150px.
4.  Add a media query to change the font size of the heading 1 (Welcome Weekend) as the screen gets larger.  The size and breakpoint are up to you.
5. At a breakpoint of 1035px, change the padding-top of the H1 to 65px and set the margin-top to 0.
6. At a breakpoint of 1300px, change the font-size of the H1 (Welcome Weekend) to 3em.
7. At 1035px, set the entire header element (<HEADER>) to become aligned to the left.  Set the header's max width to 900px and display it as block.  Set the header height to 150px.  Finally, center the header itself using an auto margin on the left and right.
8. At around 1035px set the Welcome Weekend logo to be 175px.  Also, set it to float to the left.  Set the margin to 0 .75em inherit 1.5em.
9. At 1300px, set the header's max width to 1200px, margin-top of 1em and height of 170px.
10. At 1300px, change the margin-left on the Welcome Weekend logo to 3% and up the width to 190px.


### Figures and Images

We're going to set the images to float to the left of the text at larger screen sizes.

1. Start the width of figures (aka your main image) at 100%.  Remove the padding on the figure.  Change the positioning to relative (this will allow text to flow around it).
2. Starting at 825px, float the image to the right.  Change the width to 50% and set a margin-top of 2em and a padding-left of 5%.  Set a margin-bottom of 1em.

### Figure Caption

As the screen gets larger, choose a breakpoint to change the figcaption element (the caption of your main image) to an overlay on top of the image.  

1.  At 550px, change the positioning of figcaption to absolute, add bottom: 9px, add a Kent State blue background color (using rgba) at 80% opacity.  
2.  At 550px, change the color of the text to white.  
3.  At 550px, Add a margin-left and margin-right of 5px.  
4.  At 550px, Add padding of .75em.  
5.  At 550px, Finally, change the line height to 1.3.


### Clearfix

1.  We need to clear a float!  You need to clear floats anytime you use the float property.  Add a new class called clearfix with the following values:
clearfix:after {
  display: block;
  content: "";
  display: table;
  clear: both;
}
2.  Add the "clearfix" class to the paragraph that follows What Is Welcome Weekend?


### Footer

Almost done!  As the screen gets larger, the 3 items in the footer could be placed so that they're side-by-side.

In the section, we'll be giving items a class name.  We assign class names to an element so that we can apply the exact same styling to all elements with that class.  Get used to classes - we'll be using them a lot.

1. First, we need to make an edit to the HTML.  Add a DIV around each of the pieces of contact information in the footer with a class of "contact" - one for address, one for phone, one for email.
2. At 1000px, set the footer to have a max-width of 900px and center it in the middle of the page using an auto margin on either side.
3. At 1000px, set the "contact" class to float to the left.  Set it to be 33.3% width and add padding-top of 1em and padding-bottom of 2em.

If you did the 3 steps correctly, at 1000px you should see the 3 pieces of contact information pop right beside each other, each taking up exactly 1/3 of the container.

Your end result should look [something like this](/img/layout-screenshot.jpg), knowing that you may have chosen different typefaces and breakpoints than I did.

### Submitting the Assignment

1. Once you're satisfied, go to Choose a View > Full Page > Copy the Live URL. 
2. View your newly completed website as a web page on different devices.  Does everything render correctly?
3. After you've completed your testing, log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste both the URL of the Pen (Editor Mode) as well as the Full View  URL.  Click Submit.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **4 - 5**: CSS and accompanying media queries is written appropriately and with proper indentation.  All steps were followed and correct styles are applied.  Styles are added efficiently, for example, multiple H1 styles are grouped together, as opposed to separate styles for everything.  
* **2 - 3**: CSS is mostly structured correctly, but there are some syntax and/or media query issues (for example, you forgot to close a rule with a semicolon).  Some of the steps were missed.  Similar styles are not grouped together.
* **0 - 1**: CSS does not use appropriate style attributes.  Media queries are not set correctly.  Syntax is incorrect and many of the steps were missed. The pen was not set up or submitted according to instructions.