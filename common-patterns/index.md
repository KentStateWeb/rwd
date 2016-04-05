---
layout: default
title: Common RWD Patterns
---

# Common RWD Patterns

Starting out a new responsive web site can be intimidating.  To help you get started, I've provided some of the most common patterns used across responsive websites that you can simply copy and paste, or modify for your own use.

These patterns use very light styling, with the assumption that you'll add your own CSS.

To learn more about creating accessible and maintainable patterns, pick up Ethan Marcotte's newest book, [Responsive Design Patterns and Principles](https://abookapart.com/products/responsive-design-patterns-principles). 

Also see [This is Responsive](https://bradfrost.github.io/this-is-responsive/patterns.html) by Brad Frost, where I found many of these examples. 

----

## Default HTML Code 

Just put this at the beginning of every new HTML document you create - don't try to memorize it.  

<script src="https://gist.github.com/challahan/08eddc8da7152f483f99.js"></script>

----

## CSS Reset Stylesheet

This is by no means required, but by adding this default CSS, you'll ensure maximum consistency in CSS between browsers.  

I also added in some default responsive image styles and box-sizing: border-box by default, as I always use these.

[View the Code Here](https://gist.github.com/challahan/33beaed4647a8e1f077c90085545c383)

----

## How to Use JavaScript/JQuery

Use these instructions for patterns below that require JavaScript and/or Jquery.

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/LNORrr/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/LNORrr/'>How to Use JavaScript + Jquery</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Main Content Area with SideBar

A common layout pattern start with main content and sidebar stacked until you reach a larger breakpoint, at which point the elements are floated left and right.

**Uses**: HTML and CSS

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/qZPyWO/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/qZPyWO/'>Main column with sidebar (Forked from Brad Frost)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Buttons

Buttons are typically just links with a special style applied to them.  

The pattern below will get you started, but of course you can customize a button to have any style you'd like.

**Uses**: HTML and CSS

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/YqrOdM/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/YqrOdM/'>Button Starter</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Equal-Width Columns

Start with three stacked pieces of content and create three side-by-side columns, when space allows.  

Note that you can change the 33% to 25% for 4 columns, 50% for 2 columns, etc.

**Uses**: HTML and CSS

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/jqGpOv/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/jqGpOv/'>3 Equal-Width Columns (Forked from Brad Frost)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Stacked Navigation

Navigation is stacked by default and at larger screens, the navigation floats horizontally.

**Uses**: HTML and CSS

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/YqrjpV/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/YqrjpV/'>Stacked Top Link Navigation (Forked from Brad Frost)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Basic Toggle Navigation

Start your menu as a toggle menu for small screens.  When there is room, the toggle disappears and displays the full menu horizontally.

**Uses**: HTML, CSS and JavaScript with Jquery

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/ZWXjGZ/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/ZWXjGZ/'>Toggle Navigation (Forked from Brad Frost)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Basic Toggle Navigation with Hamburger

People seem to love this pattern, so I'm including it here.  In my example, I kept the menu label and added an additional element for the hamburger icon (which animates).

**Uses**: HTML, CSS and JavaScript with Jquery

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/qZPMro/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/qZPMro/'>Toggle Navigation - with Hamburger Menu</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

## Off Canvas Navigation

This popular navigation style pushes the content area over to reveal the navigation at small screens.  At large screens, the full navigation shows horizontally, although the toggle breakpoint could be removed and display at all screen sizes.  

I modified this to include an overlay and close button for the navigation.

Also see [a version with the navigation revealed from the top](http://codepen.io/challahan/pen/ONxwwo).

**Uses**: HTML, CSS and JavaScript with Jquery


<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/YqrjNV/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/YqrjNV/'>The Left Nav Fly Out (Forked from Brad Frost)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Priority+ Navigation

At smaller screens, only the most important navigation items are shown, with a toggle to turn on the rest of the options.  At larger screens, all of the options are shown.

**Uses**: HTML, CSS and JavaScript with Jquery


<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/LNzBXL/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/LNzBXL/'>Priority+ Navigation (Forked from Brad Frost)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## CSS-Only Accordions

Achieve an accordion effect using only HTML and CSS.

**Uses**: HTML and CSS

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/BKwObo/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/BKwObo/'>Pure CSS Accordion Using Radio Buttons (Fork from Andor Nagy)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

---

## Tabs/Accordions

This accordion/tab pattern shows accordions by default, and then switches to tabs at larger breakpoints.

**Uses**: HTML, CSS and JavaScript


<iframe height='268' scrolling='no' src='//codepen.io/BeyondHyper/embed/xZXXzj/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/BeyondHyper/pen/xZXXzj/'>A11y Responsive Tabs (vanilla js)</a> by Derick Montague (<a href='http://codepen.io/BeyondHyper'>@BeyondHyper</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Vertically Centered Text on Top of Image

**Uses**: HTML and CSS

People commonly want to center text vertically on top of an element (such as an image).  This uses flexbox to easily position elements both vertically and horizontally on top of the element, and adds some tinting on top of the image for readability.

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/VaMBgy/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/VaMBgy/'>Vertically-Centered Text on Centered on Top of Image (Flexbox)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Slider/Carousel

**Uses**: HTML, CSS and JavaScript with Jquery

There are thousands of image carousels on the internet.  I like one called Flickity because the HTML markup is minimal and it supports touch.  Here's a simple implementation.

**Uses**: HTML, CSS and JavaScript (can either download the CSS/JS files or reference them from Flickity)

You can also download and customize Flickity at [http://flickity.metafizzy.com](http://flickity.metafizzy.co).

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/dMVqKQ/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/dMVqKQ/'>Flickity Slider (JavaScript)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Skip to Main Navigation (Accessibility)

Not really anything to do with responsive design, but add this code to your website to ensure users on screen readers can skip past your main navigation directly to your content.  I put this on all of my sites.

<iframe height='268' scrolling='no' src='//codepen.io/joe-watkins/embed/rjhiK/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/joe-watkins/pen/rjhiK/'>Skip to main content pattern</a> by Joe Watkins (<a href='http://codepen.io/joe-watkins'>@joe-watkins</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Clearfix

If you're using floats and your elements below the float aren't displaying properly (for example, they aren't calculating the height of the prior element correctly or aren't starting on the right line), you probably need to apply a clearfix.

<script src="https://gist.github.com/challahan/a8c38d1e92fea18b15146459e094b8b5.js"></script>