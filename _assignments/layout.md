---
title: "Fonts and Media Queries"
description: "Description of the assignment"
type: "mini"
points: 6
layout: assignment
date: 2016-11-01 12:00:00
semester: fall-2016

---

We're returning back to our Welcome Weekend website!  We have a good HTML structure in place as well as our basic CSS Styles, but now it's time to make sure the website uses our brand fonts as well as adjusts itself as the screen gets larger.

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

Open your CSS Basics 2 assignment.  Instead of editing the original pen, click the "Fork" option at the top.  Click Settings and rename the forked pen using this structure: "Your Last Name - Layout/Media Queries".

Remember these guidelines:  a. Order your media queries from smallest to largest  b. Organize your CSS by element (for example, header and footer)  and  c. Remember your first media query is no media at all.  These are your default styles.

### Choose New Fonts

1. Replace the sans-serif and serif typefaces in the document with a Google Web Font.  Go to [https://www.google.com/fonts](https://www.google.com/fonts) and choose one serif and one sans-serif typeface (whatever you think fits).
2. Under the "use" tab select your desired weights and then copy the code from the "Import" tab under step 3.
3. Copy this import code (step 2) into the top of your CSS in CodePen.  If you used the <link> option, put this code in your HTML.
4. Replace the font-family values in your CodePen with the values for the fonts you selected.

### Typography Changes

It's time to implement your first media query.  For this part, we're going to be making the paragraph and heading text get larger as the screen gets bigger.  

***Remember, the first media query is no media query at all.  This is your default (mobile) state.  Only add a media query when you need to tweak a style as the screen gets larger.***

1.  Set paragraph font size to get slightly larger at 600px.
2.  Set the paragraph font size to get even larger at 1300px.  
3.  Also, increase the paragraph line-height to increase readability at 1300px.
4.  Bump the H2's only up when the screen gets big enough.  The size is your choice.

### Main Content Area

1.  At 825px, change the main area's padding to be 3.5em, but the padding at the top only to be .5em.
2. At 1300px, change the main area's width to 1200px (this will stop it from getting any larger).


### Floated image

Change the image to float left at a breakpoint.


### Absolutely Positioned caption

Position the caption on top of the image.

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


### Quotes

1. Change blockquotes to start at a width of 90% and 1.2em font size.
2. Choose a breakpoint for the blockquote to change to an 80% width and increase its font-size again.


### Submitting the Assignment

1. Once you're satisfied, go to Choose a View > Full Page > Copy the Live URL.
2. View your newly completed website as a web page on different devices.  Does everything render correctly?
3. After you've completed your testing, log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste both the URL of the Pen (Editor Mode) as well as the Full View  URL.  Click Submit.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **5 - 6**: CSS and accompanying media queries is written appropriately and with proper indentation.  All steps were followed and correct styles are applied.  Styles are added efficiently, for example, multiple H1 styles are grouped together, as opposed to separate styles for everything.  
* **3 - 4**: CSS is mostly structured correctly, but there are some syntax and/or media query issues (for example, you forgot to close a rule with a semicolon).  Some of the steps were missed.  Similar styles are not grouped together.
* **0 - 2**: CSS does not use appropriate style attributes.  Media queries are not set correctly.  Syntax is incorrect and many of the steps were missed. The pen was not set up or submitted according to instructions.
