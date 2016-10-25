---
title: "CSS Basics 2"
description: "Description of the assignment"
type: "mini"
points: 5
layout: assignment
date: 2016-10-25 12:00:00
semester: fall-2016
status: assignment-completed


---

You're happy with the content on your Welcome Weekend website (that you made in HTML 2).  It's time to add some visual styles to the website using CSS.

CodePen makes adding CSS easy because it automatically links your stylesheet to your HTML.  When we begin coding outside of CodePen, you will have to set your CSS using a <link> tag.

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

Open your HTML Basics 1 assignment.  Instead of editing the original pen, click the "Fork" option at the top.  Click Settings and rename the forked pen using this structure: "Your Last Name - CSS Basics 2".

### Add HTML5 Layout Elements and Set Background

1. First, we need to add some HTML5 elements to surround our main sections of content: the header, main content area and footer.  In the HTML, surround the header logo and H1 with a header tag.  Surround the main content with a main tag (starting with figure and ending with the embedded video).  Surround the footer with a footer tag, starting with Student Success Programs and ending with the contact information.  Now we can target each of these areas separately with different CSS, plus they're now semantically accessible to screen readers.  If you're confused on this part, read HTML&CSS Book Chapter 17.
2.  Make everything on the page a sans-serif typeface.  
3.  Add a blue background color to the entire page of rgb(0,38,100),

### Format the Headings

1.  Make your H1 (Welcome Weekend) have the following attributes: (a) a font-size of 2.3em, (b) letter spacing of 1px, (c) use the "Garamond, Georgia, serif" font family, (d) normal font weight (e) a top margin of .25em, (f) a text shadow of 1px 1px 2px rgba(0,0,0,.9).
2. Make the H2's (your subheading styles) the same color blue as the background.  
3. Adjust the margins of your H2's (your subheading styles) so that the top margin is 2em and the bottom margin is 0.5em.  This adds more space at the top than at the bottom.

### Style the Header (Welcome Weekend)

1. Align everything in the header to be centered (hint - use text-align).  Change all of the text in the header to be colored white.
2. We need to set a size for the Destination Kent State logo.  However, we only want to affect that image and not the other images on the page.  Add a class name directly to the DKS logo image within the HTML (you can choose any class name you like - hint:  use something like class="dks-logo").
3.  Target that class in the CSS so that the DKS logo image only is 150px wide (Hint: you'll need to use a dot to call the class in the CSS).
4.  Give the DKS logo image a top margin of 1em.  This helps separate it from the top of the page.

### Style the Main Content Area and Paragraphs

1. Make the main content area have a 95% transparent white background color.  Use the background color rgba(255,255,255,.95).  
2.  Also add the following attributes to the main content area: (a) Padding of 1.5em, (b) set the width to be 90%, (c) margin: 0 auto (this centers it in the middle of the page), (d) round the corners at 5px, (e) set a maximum width of 900px (hint use max-width), (f) set a slight shadow on the main content area using these values using box-shadow: 1px 1px 3px rgba(0,0,0,.8).
3.  Give all paragraphs a line height of 1.5.
4. Set all of the images and iframes on the page to be a maximum width of 100% (use max-width) so that they never overflow their container.
5. Set all blockquotes to closely [match this style](/img/quote.png).  Set the blockquote width to 70% and center the quote in the middle of the page.
6. If your cite tag does not appear inside of the blockquote tag, you have to set cite to display:block in order for it to have a margin and appear on its own line.
7. Set the figure (which should contain both the image and caption) to take up 70% of the page as well and center it in the middle of the page.  Add padding to the top and bottom of the figure to space it out away from surrounding elements.
8. Give the photo of welcome weekend (which is an image inside of a figure tag) a 5px white border.  Give it a box shadow using this value: 1px 1px 3px rgba(0,0,0,.2).
9. Make the figcaption have a margin to space things out away from the image.  Make the font italic, .8em and align it to the center.

### Style the Table

1. Make the table have the following attributes: (a) .8em font-size, (b) a line-height of 1.3.  
2.  You'll notice that the table begins to overflow its container at small screens.  Set the following additional attributes: (a) width: 100%, (b) overflow-x: auto, (c) display: inline-block.  After setting these, you'll notice that the table gets a scrollbar at small screen widths instead of overflowing the container.
3. Give all table cells (td's) .5em of padding and 1em of padding on the bottom.
4. Make the table's header row stand out.  Make the TH elements have a background color of rgb(0,157,216), the text color white, .5em of padding and align the text to the left.

### Style the Footer

1. Almost done!  Now, make the heading in the footer (Student Success Programs) appear in gold: #eaab00.  You'll need to do this by only targeting headings that appear in the footer.
2. Style the DT elements to appear in gold as well, make them uppercase with a font size of .9em, bold and a bottom margin of .5em.
3.  Make the DD Elements have a left margin of 0, a bottom margin of 1em, a font-size of .9em and a 1.5 line height.
4. You'll notice that the email address is unreadable because links by default are blue.  To fix this, make all links (a tags) in the footer appear in white.
5. Give the footer 1em padding on the bottom so that there's some breathing room at the end of the window.
6.  Set everything in the footer to be centered using text-align.

### Change Box-Sizing

Finally, you'll notice that some of the elements still continue to overflow on small screens.  That's because of the extra padding and borders we've added cause widths to become greater than 100%.  

To fix this, add this global style to make all boxes take their borders into account.  Use * { box-sizing: border-box; }

### Submitting the Assignment

1. Once you're satisfied, go to Choose a View > Full Page > Copy the Live URL.
2. View your newly completed website as a web page on different devices.  Does everything render correctly?  Your final product should look something [close to this](/img/css2-assignment-screenshot.png).
3. After you've completed your testing, log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste both the URL of the Pen (Editor Mode) as well as the Full View  URL.  Click Submit.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **4 - 5**: CSS is written appropriately and with proper indentation.  All steps were followed and correct styles are applied.  Styles are added efficiently, for example, multiple H1 styles are grouped together, as opposed to separate styles for everything.  
* **2 - 3**: CSS is mostly structured correctly, but there are some syntax issues (for example, you forgot to close a rule with a semicolon.  Some of the steps were missed.  Similar styles are not grouped together.
* **0 - 1**: CSS does not use appropriate style attributes.  Syntax is incorrect and many of the steps were missed. The pen was not set up or submitted according to instructions.
