---
title: "Layout/Media Queries"
description: "Description of the assignment"
type: "mini"
points: 5
layout: assignment
date: 2015-11-03 12:00:00
---

We're returning back to our Welcome Weekend website!  We have a good HTML structure in place as well as our basic CSS Styles, but now it's time to make sure the website uses space efficiently while at the same time displaying well on all screen sizes.  

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

Open your HTML Basics 2 assignment.  Instead of editing the original pen, click the "Fork" option at the top.  Click Settings and rename the forked pen using this structure: "Your Last Name - Layout/Media Queries".

### Choose New Fonts

1. Replace the sans-serif and serif typefaces in the document with a Google Web Font.  Go to [https://www.google.com/fonts](https://www.google.com/fonts) and choose one serif and one sans-serif typeface (whatever you think fits).
2. Under the "use" tab select your desired weights and then copy the code from the "Import" tab under step 3.
3. Copy this import code into the top of your CSS in CodePen.
4. Replace the font-family values in your CodePen with the values for the fonts you selected.

### Header 

1.  Set the heading 1 to a smaller font-size, so that the text fits small screens better.  
2.  Add a media query to change the font size of the heading 1 as the screen gets larger.  The size and breakpoint are up to you.
3. At a breakpoint of 1035px, change the padding-top of the H1 to 65px and set the margin-top to 0.
4. At a breakpoint of 1300px, change the font-size of the h1 to 3em.
5. At 1035px, set the header to become aligned to the left.  Set the header's max width to 900px and display it as block.  Set the header height to 150px.  Finally, center the header itself using a margin.
6. At 1300px, set the header's max width to 1200px, margin-top of 1em and height of 170px.
7. Set the Welcome Weekend logo to start out at a smaller width of around 80px.
8. At around 600px, change the Welcome Weekend logo to be 150px.
9. At around 1035px set the Welcome Weekend logo to be 175px.  Also, set it to float to the left.  Set the margin to 0 .75em inherit 1.5em.
10. At 1300px, change the margin-left on the Welcome Weekend logo to 3% and up the width to 190px.

### Typography Changes

1.  Set paragraphs to get slightly larger at 600px.
2.  Set them to get even larger at 1300px.  Also, increase the line-height to increase readability.
3. Bump the H2's up when the screen gets big enough.  The size is your choice.
4. Set a margin-top on the H2's at 600px.

### Main Content Area

1.  At 825px, change the main area's padding to be 3.5em, but the padding at the top should be .5em.
2. At 1300px, change the main area's maximum width to 1200px.


### Figures and Images

1. Start the width of figures at 100%.  Remove the padding on the figure.  Change the positioning to relative.
2. At 825px, float the image to the right.  Change the width to 50% and set a margin-top of 2em and a padding-left of 5%.  Set a margin-bottom of 1em.
3. As the screen gets larger, choose a breakpoint to change the figcaption to an overlay on top of the image.  Change the positioning of figcaption to absolute, add bottom: 9px, add a Kent State blue background color at 80% opacity.  Change the color of the text to white.  Add a margin-left and margin-right of 5px.  Add padding of .75em.  Finally, change the line height to 1.3.

### Quotes

1. Change blockquotes to start at a max-width of 90% and 1.2em.
2. Choose a breakpoint for the blockquote to change to 80% max-width and increase its font-size.
3. Change the cite tag to have a margin-left of 5%.  At the same time you change your blockquote to 80% width, change the left margin of the cite tag to 10%.


### Clearfix

1.  We need to clear a float!  Add a new class called clearfix with the following values:
clearfix:after {
  display: block;
  content: "";
  display: table;
  clear: both;
}
2.  Add the "clearfix" class to the paragraph that follows What Is Welcome Weekend?


### Footer

1.  Almost done!  As the screen gets larger, the 3 items in the footer could be placed so that they're side-by-side.
2. First, we need to make an edit to the HTML.  Add a DIV around each of the pieces of contact information in the footer with a class of "contact" - one for address, one for phone, one for email.
3. At 1000px, set the footer to have a max-width of 900px and center it in the middle of the page.
4. Set the contact class to float to the left.  Set it to be 33.3% and add padding-top of 1em and padding-bottom of 2em.
5. At 1000px, you should see the 3 pieces of contact information pop right beside each other, each taking up exactly 1/3 of the container.


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