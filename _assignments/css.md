---
title: "CSS Basics"
description: "Style your conference website using basic CSS."
type: "mini"
points: 4
layout: assignment
date: 2016-10-11 12:00:00
semester: fall-2016

---

You're happy with the content on your Media Ethics conference website (that you made in HTML 1).  It's time to add some visual styles to the website using CSS.

CodePen makes adding CSS easy because it automatically links your stylesheet to your HTML.  When we begin coding outside of CodePen, you will have to set your CSS using a <link> tag.

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

Open your HTML Basics 1 assignment.  Instead of editing the original pen, click the "Fork" option at the top.  Click Settings and rename the forked pen using this structure: "Your Last Name - CSS Basics 1".

### Heading Styles
1. Set the main heading (H1) to be the conference's brand color of green: #57b9cb.  
2.  Set the Heading 1 to appear at 2.5em.  
3.  Set the Heading 1 to appear in all uppercase.
4. Set the remaining headings (H2, H3) to be the conference's brand color of red: rgb(222,26,32) - remember you can set colors using a hexcode, RGB or HSL value, which can be found in a program like Photoshop.

### Header Styles
1. Add a gray background color behind the H1 to make it more readable and appear as a banner.  Use the color #646464.
2. Set the Heading 2 (Poynter KSU Media Ethics Workshop) to appear in italics.
3. Center align the H1 and H2 text.
4. Add a subtle black text shadow onto the H1.  Use 1px 1px 3px rgba(0,0,0,.3) .
5. Add the following padding property to the Heading 1.  Note: we'll learn more about this in the next lesson - padding: 1em;

### Body Styles

1. Set all of the text on the page to display in a sans-serif typeface by default.  This should all be done using a single rule.
2. Set all links to appear bold to make them stand out.  
3.  Also, set the links on the page to appear in the brand color of green: #57b9cb;
4. Change the line-height of the paragraph text (P's) to be 1.3, so that there's a bit more spacing between lines.
4. Set all links to darken when the mouse hovers over them.  Use this slightly darker green: #3c8b99;
5. Remove the bullets from the unordered bulleted lists.  
6.  Add a property to make unordered bulleted lists have a left padding of 1em:  padding-left: 1em;
7. Set padding on the body element to 2em.  Note: we'll learn more about this in the next lesson.

### Add CSS Comments

1.  Attempt to group and organize your CSS styles into groups separated with CSS comments.  The groups should be Header (basically the H1), Headings, Body, Links, Paragraphs and Lists.
2. Adding comments and organizing your CSS styles makes them easier to locate, especially when your stylesheet gets to be several hundred lines.


### Submitting the Assignment

1. Once you're satisfied, go to Choose a View > Full Page > Copy the Live URL.
2. View your newly completed website as a web page on different devices.  Does everything render correctly?  Your final product should look something [close to this](images/cssbasics1.png).
3. After you've completed your testing, log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste the URL of the Pen (Editor Mode).  Click Submit.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **3-4**: CSS is written appropriately and with proper indentation.  All steps were followed and correct styles are applied.  Styles are added efficiently, for example, multiple H1 styles are grouped together, as opposed to separate styles for everything.  
* **2**: CSS is mostly structured correctly, but there are some syntax issues (for example, you forgot to close a rule with a semicolon.  Some of the steps were missed.  Similar styles are not grouped together.
* **0 - 1**: CSS does not use appropriate style attributes.  Syntax is incorrect and many of the steps were missed. The pen was not set up or submitted according to instructions.  
