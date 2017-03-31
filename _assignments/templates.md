---
title: "HTML/CSS Final Templates/Patterns"
description: "We're now on our way to making a real, functioning website.  "
type: "project"
points: 20
layout: assignment
date: 2017-05-09 11:00:00
semester: spring-2017
---

We're now on our way to making a real, functioning website.  For the purposes of this project, we will be producing three prototype templates that would eventually become the website.  Using these three templates, we would easily be able to do produce the rest of the site.

Instead of producing all of the templates at once, we'll split this assignment into 4 parts over the last part of the semester. (Details to be added)

1.  Basic Wireframe Structure and Mockups: April 11
2.  Patterns 1: April 18
3.  Patterns 2: April 25
4.  Combined Templates and Patterns - Instructor Review: May 2
5.  Final Templates and Patterns: May 9


## Basic HTML Wireframes

You've already sketched out your site on paper and developed a lot of the core content.  Now we need to start developing your content into HTML wireframes.  The wireframes will be built mobile-first and demonstrate the content priority in each of your 3 templates.

Remember, the wireframes don't need to be "pretty" yet.  We're going to create the structure first, and then slowly add style and layout (including responsive breakpoints) to our templates through CSS.

1.  Create a new folder in your project repository and call it "wireframes".  
2.  Inside the folder, create three individual HTML files.  One is going to be called index.html (which will be your home page template).  The other two are your choice, depending on which 2 other templates are most important for your website.  For example, a Product page might be considered a template.  You don't have to create a separate template for each Product, since they will all follow the same basic format.
3. Create a structure for each of the HTML pages, based on your content.  Most of your sites will include a header and footer.  The rest of the content elements are up to you.  Don't forget to add the required HTML DOCTYPE code in the HTML files.
4. Use semantic HTML to mark up your content.  For example, you might surround your main content using the MAIN HTML template and the header using the HEADER tag.  Some elements will be surround by DIVs with class names (for example, a DIV called "menu-item").
5. If your site uses navigation, mark it up using an unordered list.  We'll style it to look like a menu later.
6. Add real content into your 3 templates.  The content should be representative of the actual content that will be on the website, not lorem ipsum.  Links need not work right now.  You can link to a "#" if the link is not available.
7. Once you have created your three templates, create a new file called "style.css".  This is where your styles will eventually go.
8. Link your stylesheet to each of your main templates, using the code below.
9. Add a few default styles to make your templates a bit easier to view.  Use the CSS below.

### Adding a Stylesheet Link


<script src="https://gist.github.com/challahan/08eddc8da7152f483f99.js"></script>

### Adding Wireframe Styles


<script src="https://gist.github.com/challahan/8d1a513d126feb7e69ce.js"></script>

## What To Do

This will likely be the most challenging part of the project because it involves putting everything together that you've learned thus far.  

1.  Take the folder that you previously created for your HTML wireframes and duplicate it.  
2. Name the duplicated folder "templates".
3. These are the three template files that you'll be working with for the rest of the semester.

## Adding Styles

You've already created a stylesheet (style.css).  This is where you'll style each of your elements, using the appropriate class and HTML element names.  I'm not going to be too specific here, because each of your projects will vary.  However, when completed, your HTML templates will be fully styled with CSS that follows the design language you created in your style tiles.

You may find that you need to create a few page layout mockups in Sketch in order to visualize all of your elements together in a single view.  This is totally fine.  I won't be reviewing your mockups - only the final templates.  If you are doing mockups, just design enough to get you started.  You should refine your designs using your HTML templates.

Your templates should be fully responsive and use appropriate media queries and breakpoints.

If you are using a single-scroll template, you should include three distinct sections within your page.



## How to Turn In the Assignment

You'll be submitting your templates via your GitHub repository.

1.  Make sure your three templates are placed in the "templates" folder
2.  On your root index.html file, which is the Project Hub, add an H2 with Date: Templates.
3.  Add a link to your three templates under the Templates section.  Name each link with the title of the template, for example "Product Page Template".
4.  After you've commited and synced your changes via GitHub Desktop, you can submit both the timeline hyperlink and the link your three templates via Blackboard Learn.  Note: Don't link to the local version on your computer.  You need to access the live version on the web with the GitHub.io URL.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **8-10**: You've put everything you've learned so far together.  Your templates' HTML and CSS uses the appropriate content and styles.  Your templates form a cohesive whole, but also demonstrate a unified design system.  Your HTML is structured well, and you are using appropriate breakpoints in your CSS. Your website renders correctly on popular phones, tablets and desktop computers.
* **4-7**: You've put together the templates, but they don't always show a unified design system.  Some of the content is missing or not in appropriate places.  There are some issues with the responsive breakpoints - more testing may be needed on different sized screens or devices.  There are also a few HTML and CSS errors.
* **0 - 3**: The design system for your templates is week and templates don't follow the structure of your content.  HTML and CSS structure is weak and doesn't follow what you've learned in class.   A lot more work is required to make the templates ready for client review.
