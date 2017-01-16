---
title: "Fonts and Media Queries"
description: "Description of the assignment"
type: "mini"
points: 6
layout: assignment
date: 2017-02-28 12:00:00
semester: spring-2017
##status: assignment-completed

---

We're returning back to our Welcome Weekend website!  We have a good HTML structure in place as well as our basic CSS Styles, but now it's time to make sure the website uses our brand fonts as well as adjusts itself as the screen gets larger.

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

Open your CSS Basics 2 assignment.  Instead of editing the original pen, click the "Fork" option at the top.  Click Settings and rename the forked pen using this structure: "Your Last Name - Layout/Media Queries".

Remember these guidelines:  

* a. Order your media queries from smallest to largest  
* b. Organize your CSS by element (for example, header and footer)
* c. Your first media query is no media at all.  These are your default styles.

### Choose New Fonts

1. Replace the sans-serif and serif typefaces in the document with a Google Web Font.  Go to [https://www.google.com/fonts](https://www.google.com/fonts) and choose one serif and one sans-serif typeface (whatever you think fits) by clicking the "Select this Font option".
2. At the bottom of the screen you'll see "2 Families Selected".  Select this box and choose the @IMPORT option.
3. Copy this import code into the top of your CSS in CodePen.  Do not include the "Style" tags.  If you used the Standard option instead, put this code in your HTML.
4. Replace the font-family values in your CodePen with the values for the fonts you selected.  See the Specify in CSS section on Google Fonts for the correct way to define your fonts in your CodePen CSS.

### Typography Changes

It's time to implement your first media query.  For this part, we're going to be making the paragraph and heading text get larger as the screen gets bigger.  

***Remember, the first media query is no media query at all.  This is your default (mobile) state.  Only add a media query when you need to tweak a style as the screen gets larger.***

1.  Set all paragraph font sizes to get slightly larger at a minimum width of 600px.
2.  Set all paragraph font sizes to get even larger at a minimum width of 1000px.  
3.  Increase all paragraph line-heights at a minimum width of 1000px.
4.  Increase all H2 font sizes at a minimum width of 1000px.

### Main Content Area

1.  At a minimum width of 825px, change the main area's padding to be 3.5em, but the padding at the top only to be 1em.
2. At 1000px, change the main area's width to be fixed at 1200px (this will stop it from getting any larger).


### Floated image

Now we're going to set the welcome weekend image to float to the right of the text at larger screen sizes.

1. Starting at a minimum width of 825px, float your "figure" element to the right.  
2. Starting at a minimum width of 825px, change the width of your figure element to 50%.
3. Starting at a minimum width of 825px, set a margin-top of 2em and a padding-left of 5% to your figure element.  
4. Starting at a minimum width of 825px, set a margin-bottom of 1em to your figure element.

If you've done everything correctly, you should see your image float within the text starting at 825px.


### Absolutely Positioned caption

As the screen gets larger, choose a breakpoint to change the figcaption element (the caption of your main image) to overlay on top of the image.  

1.  Starting at a minimum width of 550px, change the positioning of figcaption to absolute.
2.  Starting at a minimum width of 550px, add bottom: 9px to figcaption.
3.  Starting at a minimum width of 550px, add a Kent State blue background color (using rgba) at 80% opacity to figcaption.  
4.  Starting at a minimum width of 550px, change the color of the figcaption text to white.  
5.  Starting at a minimum width of 550px, Add a margin-left and margin-right of 5px to figcaption.  
6.  Starting at a minimum width of 550px, Add padding of .75em to figcaption.  
7.  Your caption likely isn't on top of your image!  That's because we need to tell the caption to position itself relative to the "figure" element.  Go back to your default "figure" styles and add "position: relative" to the figure element.  You should see the caption now positions itself on top of the image at 825px.  Check your HTML - "figcaption" must be inside of "figure" in order for this to position correctly.  If it is not, adjust your HTML.


### Submitting the Assignment

Your final product should look something close to mine, understanding that your fonts and screen widths will vary.  See the [Small Screen Version](/img/fonts-small.png) and [Large Screen Version](/img/fonts-large.png).

1. Once you're satisfied, go to Choose a View > Full Page > Copy the Live URL.
2. View your newly completed website as a web page on different devices.  Does everything render correctly?
3. After you've completed your testing, log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste both the URL of the Pen (Editor Mode) as well as the Full View  URL.  Click Submit.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **5 - 6**: CSS and accompanying media queries is written appropriately and with proper indentation.  All steps were followed and correct styles are applied.  Styles are added efficiently, for example, multiple H1 styles are grouped together, as opposed to separate styles for everything.  
* **3 - 4**: CSS is mostly structured correctly, but there are some syntax and/or media query issues (for example, you forgot to close a rule with a semicolon).  Some of the steps were missed.  Similar styles are not grouped together.
* **0 - 2**: CSS does not use appropriate style attributes.  Media queries are not set correctly.  Syntax is incorrect and many of the steps were missed. The pen was not set up or submitted according to instructions.
