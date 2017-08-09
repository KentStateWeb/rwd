---
title: "Fonts and Media Queries"
description: "Description of the assignment"
type: "challenge"
points: 6
layout: assignment
date: 2017-02-28 12:00:00
semester: fall-2017
##status: assignment-completed

---

We're returning back to our Welcome Weekend website!  We have a good HTML structure in place as well as our basic CSS Styles, but now it's time to make sure the website uses our brand fonts as well as adjusts itself as the screen gets larger.

This is an individual assignment, and it will be turned in via Blackboard Learn.  

**Do not copy and paste another student's code.  If I catch you doing so, you'll receive a 0 for the assignment.**

## What To Do

Open your CSS Basics 2 assignment.  Instead of editing the original pen, click the "Fork" option at the top.  Click Settings and rename the forked pen using this structure: "Your Last Name - Layout/Media Queries".

You're going to be using fonts and media queries to add on to your website, making it work well at all screen sizes.

It should resemble the screenshots from these examples (remember that I may have chosen different fonts than you).

<a class="button small" href="../images/fonts/small.png">Small Screen Version</a>
<a class="button small" href="../images/fonts/large.png">Large Screen Version</a>

**Remember these guidelines:**

1. Order your media queries from smallest to largest  
2. Organize your CSS by element (for example, header and footer)
3. Your first media query is no media at all.  These are your default styles.

---

### Step 1: Choose New Fonts

You're going to replace the sans-serif and serif typefaces in the document with a Google Web Font of your choice.  

<figure class="figure">
<a href="../images/fonts/fonts.png"><img src="../images/fonts/fonts.png" alt="Fonts Example" /></a>
</figure>

1.  Go to [https://www.google.com/fonts](https://www.google.com/fonts) and choose one serif and one sans-serif typeface (whatever you think fits) by clicking the "+" icon.
2. At the bottom of the screen you'll see "2 Families Selected".  Click on this box.
3. Copy the code beginning with < link href > under Standard.
4. Paste this code into the HTML of your CodePen (preferably below your content).  This will import the fonts for use on your web page.
5. Finally, replace the font-family values in your CodePen with the values for the fonts you selected.  See the "Specify in CSS" section on Google Fonts for the correct way to define your fonts in your CodePen CSS.  For example if you chose the Oswald font, instead of "font-family: Helvetica, sans-serif" you would do "font-family: 'Oswald', sans-serif;".

---

### Step 2: Paragraph Size Adjustments

<figure class="figure">
<img src="../images/fonts/paragraph.png" alt="Heading Example" />
</figure>

It's time to implement your first media query.  For this part, we're going to be making the paragraph text get larger as the screen gets bigger.  

***Remember, the first media query is no media query at all.  This is your default (mobile) state.  Only add a media query when you need to tweak a style as the screen gets larger.***

1.  Set all paragraph font sizes to get slightly larger starting at a minimum width of 600px.
2.  Set all paragraph font sizes to get even larger at a minimum width of 1000px.  
3.  Increase all paragraph line-heights at a minimum width of 1000px.

---

### Step 3: Heading Size Adjustments

<figure class="figure">
<img src="../images/fonts/heading.png" alt="Heading Example" />
</figure>

1.  Increase all H2 font sizes at a breakpoint of your choice as the screen gets larger.

---

### Step 4: Main Content Area Size

<figure class="figure">
<img src="../images/fonts/padding.png" alt="Padding Example" />
</figure>

1.  At a breakpoint width of your choice, change the main area to have more space inside of it (padding).
2. Change the main area's maximum width to be fixed at 1200px (this will stop it from getting any larger).

---

### Step 5: Figure Image + Caption

Now we're going to set the welcome weekend image to float to the right of the text at larger screen sizes.

<figure class="figure">
<img src="../images/fonts/image.png" alt="Figure Example" />
</figure>

1. At a starting breakpoint width of your choice, float your "figure" element (which should contain an image and caption) to the right. You'll need to look up how to use the "float" property.
2. Change the width of your figure element to 50% at this same breakpoint.
3. Add space on the top, left and bottom around your figure element at this same breakpoint.

If you've done everything correctly, you should see your image float within the text starting at your breakpoint.

---

### Step 6:  Set the Logo To Get Bigger

<figure class="figure">
<img src="../images/fonts/logo.png" alt="Logog Example" />
</figure>

1.  Once there is enough room, set the Destination Kent State logo ONLY to get slightly larger (increase the width).
2.  Do this by giving the logo a CLASS name in the HTML and using that class in the CSS.  While this could be accomplished in other ways, I want you to practice using a class here.

---

### Submitting the Assignment

Your final product should look something close to mine, understanding that your fonts and screen widths will vary.  

<a class="button small" href="../images/fonts/small.png">Small Screen Version</a>
<a class="button small" href="../images/fonts/large.png">Large Screen Version</a>

1. Once you're satisfied, copy the Editor Mode URL from CodePen
2. Log in to Blackboard Learn to submit your assignment.  Go to Assignments > Assignment Name.  Under Write Submission, Paste the URL of the Pen (Editor Mode).  Click Submit.

---

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **5 - 6**: CSS and accompanying media queries is written appropriately and with proper indentation.  All steps were followed and correct styles are applied.  Styles are added efficiently, for example, multiple H1 styles are grouped together, as opposed to separate styles for everything.  
* **3 - 4**: CSS is mostly structured correctly, but there are some syntax and/or media query issues (for example, you forgot to close a rule with a semicolon).  Some of the steps were missed.  Similar styles are not grouped together.
* **0 - 2**: CSS does not use appropriate style attributes.  Media queries are not set correctly.  Syntax is incorrect and many of the steps were missed. The pen was not set up or submitted according to instructions.
