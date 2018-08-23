---
title: "CSS Basics 1"
description: "Style your conference website using basic CSS."
type: "challenge"
points: 4
layout: assignment
date: 2018-09-26 12:00:00
semester: fall-2018
#status: assignment-completed

---

You're happy with the content on your Media Ethics conference website (that you made in HTML 1).  It's time to add some visual styles to the website using CSS.

<a class="button small" href="/img/cssbasics1.png">View Sample Mockup</a>

CodePen makes adding CSS easy because it automatically links your stylesheet to your HTML.  When we begin coding outside of CodePen, you will have to set your CSS using a <link> tag.

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

Open your HTML Basics 1 assignment.  Instead of editing the original pen, click the "Fork" option at the top.  Click Settings and rename the forked pen using this structure: "Your Last Name - CSS Basics 1".

Notice how we've broken the page up into parts.  This is good practice and will help you organize your CSS better.

---

### Step 1: Global Styles

1.  Set all of the text on the page to display in a sans-serif typeface by default.  This should all be done using a single rule.
2. Set padding on the <BODY> element to give the page ample white space around the 4 sides.  Note: we'll learn more about padding in the next lesson.

---

### Step 2: Header Styles (H1)

<figure class="figure">
<img src="../images/css1/header.png" alt="Padding Example" />
</figure>

We're going to use the H1 with the words "Enduring Trauma" as our "header" and style it to look like a header.

In Atomic Design speak, we might consider the header to be a molecule because it's a more complex element.

1. Set the main heading (H1) to be the conference's brand color of green: #57b9cb  
2.  Set the Heading 1 to appear larger (use any size you think looks good)
3.  Set the Heading 1 to appear in all uppercase.
4. Add a gray background color (#646464) behind the H1 to make it more readable and appear as a banner.
5. Add padding around the H1 (we'll talk more about this in the next lesson).

---  

### Step 3: Heading Styles (H1 - H3)

<figure class="figure">
<img src="../images/css1/headings.png" alt="Padding Example" />
</figure>

Style the rest of the headings used on the page.  Headings are atoms in atomic design - the smallest components of the page.

1. Set the Heading 2 (Poynter KSU Media Ethics Workshop) to appear in italics.
2. Center align the H1 and H2 text.
3. Add a subtle black text shadow onto the H1. (You may have to look up how to do this)
4. Set the remaining headings (H2, H3) to be the conference's brand color of red: rgb(222,26,32).

---

### Step 4: Paragraphs (P)

<figure class="figure">
<img src="../images/css1/paragraph.png" alt="Padding Example" />
</figure>

Paragraphs are also considered atoms.  Style your paragraphs using the following suggestions.

1. If you set your font family correctly as a global style, it should have also affected your paragraph text and changed it to the correct font.
2. Change the line height (known as leading in print) of the paragraph text (P's) to be larger than the default, so that there's a bit more spacing between lines.

---

### Step 5: Links (A)

<figure class="figure">
<img src="../images/css1/links.png" alt="Links Example" />
</figure>

1.  Set all links to appear bold to make them stand out.  
2.  Also, set the links on the page to appear in the brand color of green: #57b9cb;
3. 4. Set all links to darken when the mouse hovers over them.  Use this slightly darker green: #3c8b99;

---

### Step 4: Lists

<figure class="figure">
<img src="../images/css1/padding.png" alt="Padding Example" />
</figure>

1.  Remove the bullets from the unordered bulleted lists.  
2.  You'll notice that your items in the unordered bulleted list are now out of line with the items in the ordered list.  This is because all lists have by default 2em (40px) of padding on their left side.  Find a way to adjust the padding on the left of the unordered lists to make it equal to the alignment of the ordered list.  We'll talk more about padding in the next lesson.

---

### Step 5: Add CSS Comments

1.  Attempt to group and organize your CSS styles into groups separated with CSS comments (these comments are formatted differently than those in HTML).  The groups should be Global, Header, Headings, Body, Links, Paragraphs and Lists.
2. Adding comments and organizing your CSS styles makes them easier to locate, especially when your stylesheet gets to be several hundred lines.

---

### Check Over Your Assignment

Does everything render correctly?  Your final product should look something close to the sample mockup.

<a class="button small" href="/img/cssbasics1.png">View Sample Mockup</a>

### Submitting the Assignment

1. Once you're satisfied, copy the Editor Mode URL from CodePen
2. Log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste the URL of the Pen (Editor Mode).  Click Submit.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **3-4**: CSS is written appropriately and with proper indentation.  All steps were followed and correct styles are applied.  Styles are added efficiently, for example, multiple H1 styles are grouped together, as opposed to separate styles for everything.  
* **2**: CSS is mostly structured correctly, but there are some syntax issues (for example, you forgot to close a rule with a semicolon.  Some of the steps were missed.  Similar styles are not grouped together.
* **0 - 1**: CSS does not use appropriate style attributes.  Syntax is incorrect and many of the steps were missed. The pen was not set up or submitted according to instructions.  
