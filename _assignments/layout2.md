---
title: "Boxes and Layout"
description: "Description of the assignment"
type: "challenge"
points: 6
layout: assignment
date: 2017-03-07 12:00:00
semester: spring-2017
##status: assignment-completed

---

This assignment begins a brand new webpage that will help you learn how to lay out and style boxes.

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

### Starter Content and HTML

It's best to start with the content and structure first, and then move on to CSS.  I've provided some HTML and content to get you started.

Visit [http://codepen.io/challahan/pen/WxagwO](http://codepen.io/challahan/pen/WxagwO) and fork my starter pen using the Fork button.

Rename the pen by clicking on the Pencil icon and renaming it to this structure: Your Name - Boxes and Layout

### Final Product

Here's what we'll be making.  Don't try to do it all at once, we'll take each section at a time.  This is a responsive website, so there will be multiple changes in layout at different breakpoints.  

#### Small Screen

<figure class="figure">
<img src="../images/small-new.png" alt="Small Image" />
</figure>

#### Large Screen

<figure class="figure">
<img src="../images/large-new.png" alt="Small Image" />
</figure>
---

### Step 1: Header

Let's start with the header (<header>).  Rather than telling you what rules to use, I'm going to provide you with an image of how the header should look.  It's up to you to style it, but it doesn't have to be exact.

1.  Use colors Blue: hsl(206,100,14), Yellow: hsl(43,100,90) (Yellow) and White.
2.  Set the header in font-family: 'Suez One', serif;
3.  In order to get the word "Boxes" on its own line, you'll need to use the "display: block" property and target the "span" around the word "boxes".
4.  Create a line above the word "boxes" using border-top.

<figure class="figure">
<img src="../images/header.png" alt="Header Image" />
</figure>

<figure class="figure">
<img src="../images/header-large.png" alt="Header Large" />
</figure>

---

### Step 2: Main Content Area

1.  Make the main content area (main) stop getting any larger than 900px wide (use the max-width CSS property).  
2.  Center this MAIN box in the middle of the page (this will only be apparent when the viewport is larger than 900px).

Note: The header and footer reside outside of the MAIN box and this therefore won't apply to them.

---

### Step 3: Navigation

The navigation (nav) starts as a stacked list, and then turns into a horizontal list.

1.  Use background color hsl(32,100,50).
2.  Remove the default bulleted style on the unordered list within the <nav> box, as well as its margin and padding.  You can do this either using "nav ul" or by adding a class to the <ul> element.
3.  Set the list items to be centered (see picture).
4.  Set the list items to be colored white.
5.  Set each list item (li) to have padding around it.
6.  Aadd a CSS media query.  When the screen gets large enough (you choose the size), use flexbox on the list to position items side-by-side.  You can do this either by targeting "nav ul" or by adding a class to the <ul> element and setting it to display: flex.
7.  Flexbox also has a property to tell each list item to take up equal space.  Hint: see the section in [CSS Tricks called "Justify Content"](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

<figure class="figure">
<img src="../images/nav-small.png" alt="Header Small" />
</figure>

<figure class="figure">
<img src="../images/nav-large.png" alt="Header Large" />
</figure>

---

### Step 4: Boxes

Now lets style all of the divs to give them equal spacing.  There are 9 individual boxes (marked up as DIVs) in between the footer and navigation.

1.  Each of the boxes have already been given identical class name of class="box".  
2.  Set a style for each .box in your CSS of padding: 2em and margin: .25em.

---

### Step 5: First Row

Now it's time to style the first row of boxes.  This one is simple.  We'll start out with each box stacked and then, at a breakpoint, change to a 50/50 layout.

Your first row has already been given the class "first-row".

1.  Make each individual box in the first row have a white background.  To do this, you'll have to use a class in your CSS: .first-row .box {background-color: white;}.
2.  At your favorite breakpoint, change the boxes in the first row to become side-by-side using display: flex.  Remember that display:flex goes on the parent box (.first-row) and not on each individual box.  Upon applying flex, the boxes will by default line up side-by-side.

<img src="../images/first-row-small.png" alt="First Row Small" />

<img src="../images/first-row-large.png" alt="First Row Large" />

---

### Step 6: Second Row

The next row is a bit more challenging.  We're going to add background images to each of the boxes, and also style the paragraphs inside to be boxes themselves, perfectly centered inside.

1.  Use this image to declare a background image for both of the boxes in the second row and use the background-image property:  https://s3-us-west-2.amazonaws.com/s.cdpn.io/259273/laptop.jpg
2.  Use the "background-size: cover" property to tell the image to always use the available background space.
3.  Two of the boxes that are inside the second row already have a class name of "inner-box".  Style the boxes inside the second-row boxes to have a background-color (hsla(197,82,38,.9) and white text.
4.  At your favorite breakpoint, use flexbox to position the two second-row boxes  side-by-side (be sure to target the .second-row class with the display: flex property).  However, instead of making them an even 50%, make the first box 25% and the second one 75%.  Hint - the only way to do this is to set a width on each of the boxes using the preexisting class names .box-left and .box-right.
5.  If you've done everything right, you'll notice that the content in the right box is not vertically centered at larger screen sizes.  You can fix this by adding display: flex; and align-items: center; to the ".right-box" styles.  This will perfectly center the content vertically.

<img src="../images/second-row-small.png" alt="Second Row Small" />

<img src="../images/second-row-large.png" alt="Second Row Large" />

---

### Step 7: Footer

Nothing special here.  Just make the footer background hsl(197,82,38), give it some padding and margin, and center the text inside.

<img src="../images/footer.png" alt="Footer" />

---

### Submitting the Assignment

Your final product should look something close to mine, understanding that your fonts and screen widths will vary.  

<a class="button small" href="../images/small-new.png">Small Screen Version</a>
<a class="button small" href="../images/large-new.png">Large Screen Version</a>

1. Once you're satisfied, copy the Editor Mode URL from CodePen
2. Log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste the URL of the Pen (Editor Mode).  Click Submit.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **5 - 6**: CSS and accompanying media queries is written appropriately and with proper indentation.  All steps were followed and correct styles are applied to match screenshots as closely as possible.  Styles are added efficiently.  
* **3 - 4**: CSS is mostly structured correctly, but there are some syntax and/or media query issues (for example, you forgot to close a rule with a semicolon).  Some of the steps were missed.  Similar styles are not grouped together.
* **0 - 2**: CSS does not use appropriate style attributes.  Media queries are not set correctly.  Syntax is incorrect and many of the steps were missed. The pen was not set up or submitted according to instructions.
