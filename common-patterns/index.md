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

A common layout pattern start with main content and sidebar stacked until you reach a larger breakpoint, at which point the elements are positioned left and right (using flexbox).

**Uses**: HTML and CSS

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/qZPyWO/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/qZPyWO/'>Main column with sidebar (Forked from Brad Frost)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Typical Page Layout (Header, Nav, Main Area, Footer)

A typical page setup - creativity away from this standard layout is encouraged though!

**Uses**: HTML and CSS

<iframe height='265' scrolling='no' title='Your Standard Header, Nav, Footer and Main Content' src='//codepen.io/challahan/embed/yVYLJa/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/yVYLJa/'>Your Standard Header, Nav, Footer and Main Content</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
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

## Adding Tint On Top of Images/Boxes

Add a tinted overlay on top of an HTML element (such as an image) with CSS.  You can adjust the tint color and percentage in the CSS (even adding a gradient instead).

<iframe height='300' scrolling='no' title='Image with Tinted Overlay' src='//codepen.io/challahan/embed/MOvaEx/?height=117&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/challahan/pen/MOvaEx/'>Image with Tinted Overlay</a> by Christopher Hallahan (<a href='https://codepen.io/challahan'>@challahan</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>


----

## Basic Toggle Navigation with Hamburger

People seem to love this pattern, so I'm including it here.  In my example, I kept the menu label and added an additional element for the hamburger icon (which animates).

**Uses**: HTML, CSS and JavaScript with Jquery

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/qZPMro/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/qZPMro/'>Toggle Navigation - with Hamburger Menu</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

---

## Off Canvas Navigation

This popular navigation style pushes the content area over to reveal the navigation at small screens.  At large screens, the full navigation shows horizontally, although the toggle breakpoint could be removed and display at all screen sizes.  

I modified this to include an overlay and close button for the navigation.

Also see [a version with the navigation revealed from the top](http://codepen.io/challahan/pen/ONxwwo).

**Uses**: HTML, CSS and JavaScript with Jquery


<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/YqrjNV/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/YqrjNV/'>The Left Nav Fly Out (Forked from Brad Frost)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Full-Screen Navigation

Displays navigation as an animated overlay on top of the main content area.  Could potentially be modified to only show this pattern at small screens using media queries.

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/GZywvr/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/GZywvr/'>Full Screen Nav</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Priority+ Navigation

At smaller screens, only the most important navigation items are shown, with a toggle to turn on the rest of the options.  At larger screens, all of the options are shown.

**Uses**: HTML, CSS and JavaScript

<iframe height='265' scrolling='no' title='PriorityNavigation.js Demo' src='//codepen.io/challahan/embed/GmKXmY/?height=265&theme-id=0&default-tab=js,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/GmKXmY/'>PriorityNavigation.js Demo</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>


Source: https://github.com/gijsroge/priority-navigation

----

## Simple CSS-only Accordion

Achieve an accordion effect using only HTML and CSS.

**Uses**: HTML and CSS

<iframe height='300' scrolling='no' title='Pure CSS Accordion - Forked from Oliver Knoblich' src='//codepen.io/challahan/embed/zPdvrQ/?height=107&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/challahan/pen/zPdvrQ/'>Pure CSS Accordion - Forked from Oliver Knoblich</a> by Christopher Hallahan (<a href='https://codepen.io/challahan'>@challahan</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

---

## Simple Tabs

Some very easily implemented tabs.  If you have many tabs, you might want to try the tab/accordion combination below for a better mobile experience

**Uses**: HTML, CSS and JavaScript with Jquery

<iframe height='268' scrolling='no' title='Tabbed Content with jQuery and CSS (Forked)' src='//codepen.io/challahan/embed/QOMbJq/?height=134&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/challahan/pen/QOMbJq/'>Tabbed Content with jQuery and CSS (Forked)</a> by Christopher Hallahan (<a href='https://codepen.io/challahan'>@challahan</a>) on <a href='https://codepen.io'>CodePen</a>.
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

Creates a carousel of images.  The example below is using the Flickity plugin, but there are many out there:

* [Flickity](http://flickity.metafizzy.co)
* [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/)

**Uses**: HTML, CSS and JavaScript (can either download the CSS/JS files or reference them from Flickity)

You can also download and customize Flickity at [http://flickity.metafizzy.com](http://flickity.metafizzy.co).

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/dMVqKQ/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/dMVqKQ/'>Flickity Slider (JavaScript)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Photo Gallery

Displays thumbnail photos as a gallery, with the option to click through for a full-screen version.

Note - this is a more advanced implementation

* [PhotoSwipe](http://photoswipe.com)

----

## Responsive Date Picker Widget ##

This is from the Pikaday Responsive date picker library.  I've reproduced all of the code you'll need for clearer implementation.

I like this date picker because it detects whether the user is on a mobile browser and instead displays the native (small-screen optimized) date picker for these browsers.

There are some additional customizations you can make and you can find them in the full documentation: <a href="https://github.com/mydea/PikadayResponsive">https://github.com/mydea/PikadayResponsive</a>

**Uses**: HTML, CSS, JavaScript and Modernizr (included in HTML)

<iframe height='268' scrolling='no' src='//codepen.io/challahan/embed/XdZKyw/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/XdZKyw/'>Responsive Date Picker Demo (using Pikaday Responsive)</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

---

## Response Modal Window/Popover

I like this modal example because it fills the entire screen on small screens, and on larger screens, allows the user to exit by tapping anywhere outside of the window.

**Uses**: HTML, CSS and JavaScript with Jquery


<iframe height='266' scrolling='no' src='//codepen.io/challahan/embed/xVaVYG/?height=266&theme-id=0&default-tab=css,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/xVaVYG/'>Responsive Modal/Popover Example</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

---

## Simple CSS-Only Content Filter

Uses pure CSS to filter a list of items by category when selected.

**Uses**: HTML & CSS


<iframe height='265' scrolling='no' title='Pure CSS content filter (Forked from Sam Gordon)' src='//codepen.io/challahan/embed/GOvJNR/?height=10&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/challahan/pen/GOvJNR/'>Pure CSS content filter (Forked from Sam Gordon)</a> by Christopher Hallahan (<a href='https://codepen.io/challahan'>@challahan</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

---

## Smooth Scroll to a Page Location (Anchor)

Scrolls user to a particular location up or down the page by clicking a link.  JavaScript adds the smooth scrolling motion.

**Uses**: HTML, CSS and JavaScript with Jquery

<iframe height='265' scrolling='no' title='Smooth Scroll Demo' src='//codepen.io/challahan/embed/VbwMgo/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/challahan/pen/VbwMgo/'>Smooth Scroll Demo</a> by Christopher Hallahan (<a href='http://codepen.io/challahan'>@challahan</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

---

## Lazy Loading Plugins

Options for intelligently loading content only when the user reaches that position on the page.  Note - these are more advanced, but provided in case you need them.

* [Lozad.js](https://github.com/ApoorvSaxena/lozad.js)
* [jQuery.Lazy](http://jquery.eisbehr.de/lazy/)

---

## CSS Animations

Easily add CSS animations to elements on your page with this animation library.

Note - you do not need to add this entire CSS file to your website - only the animations you need.

* [Animate.css](ttps://daneden.github.io/animate.css/)

---

## Skip to Main Navigation (Accessibility)

Not really anything to do with responsive design, but add this code to your website to ensure users on screen readers can skip past your main navigation directly to your content.  I put this on all of my sites.

<iframe height='268' scrolling='no' src='//codepen.io/joe-watkins/embed/rjhiK/?height=268&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/joe-watkins/pen/rjhiK/'>Skip to main content pattern</a> by Joe Watkins (<a href='http://codepen.io/joe-watkins'>@joe-watkins</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

----

## Clearfix

If you're using floats and your elements below the float aren't displaying properly (for example, they aren't calculating the height of the prior element correctly or aren't starting on the right line), you probably need to apply a clearfix.

<script src="https://gist.github.com/challahan/a8c38d1e92fea18b15146459e094b8b5.js"></script>
