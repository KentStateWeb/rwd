---
title: "HTML/CSS Final Prototype/Templates"
description: "We're now on our way to making a real, functioning website.  "
type: "project"
points: 10
layout: assignment
date: 2015-12-08 11:00:00
---

We're now on our way to making a real, functioning website.  For the purposes of this project, we will be producing three prototype templates that would eventually become the website.  Using these three templates, we would easily be able to do produce the rest of the site.

## What To Do

This will likely be the most challenging part of the project because it involves putting everything together that you've learned thus far.  

1.  Take the folder that you previously created for your HTML wireframes and duplicate it.  
2. Name the duplicated folder "templates".
3. These are the three template files that you'll be working with for the rest of the semester.

## Adding Styles

You've already created a stylesheet (style.css).  This is where you'll style each of your elements, using the appropriate class and HTML element names.  I'm not going to be too specific here, because each of your projects will vary.  However, when completed, your HTML templates will be fully styled with CSS that follows the design language you created in your style tiles.

You may find that you need to create a few page layout mockups in Sketch in order to visualize all of your elements together in a single view.  This is totally fine.  I won't be reviewing your mockups - only the final templates.  If you are doing mockups, just design enough to get you started.  You should refine your designs using your HTML templates.

Your templates should be fully responsive and use appropriate media queries and breakpoints.

## Install Jekyll

We've created three prototype files, but there are some problems.  What happens if we change the content of a global element like the header or footer?  Right now if we make a change, we have to change it in all three documents.  By setting these global elements up in a template, we can make changes just once and have them automatically update everywhere.

First, we need to setup Jekyll, a popular static website generator.  We'll do this together in class.

1.  Open terminal.  "Sudo gem install bundler".
2.  Create a new file in your project repository called "Gemfile" - there is no file extension.
3.  Inside Gemfile, add the following line: gem 'github-pages'
4.  Back in the terminal, run "bundle install"
5.  You're ready to run Jekyll.  In terminal, run "bundle exec jekyll serve".
6.  In your browser, go to http://localhost:4000 .  You'll see your site, just as you expected.

## Make Your Templates Dynamic

We're now running a Jekyll site, but we aren't benefiting from Jekyll yet.

1.  Create a folder in your project called "_includes".  The underscore is required.
2.  In your includes folder, create a file called "header.html" and "footer.html".
3.  Copy the code that makes up everything above the start of your main content area and paste it into your header file.
4.  Do the same with the footer file.  Everything below the end of your main content area.
5.  Create another new folder called "_layouts".
6.  Inside layouts, create a new file called "default.html".
7.  Inside default.html, place the code under Default Layout Template below.
8.  Open up each of your 3 templates.  Delete the header and footer from each of them.  At the very top of each, paste the code below called Default Frontmatter.
8.  Open your site back up in your web browser at http://localhost:4000 and navigate to your templates.  You'll see that all three pages display as expected with the same header and footer.  The difference now is that the header/footer is shared.  Try making a change to the header under the "_includes" folder.  You'll notice that the change is reflected automatically on all three templates!
9. Move your stylesheet.css file into the root folder calledd "style" (it should have been created automatically by Jekyll).  We're going to be referencing this file from different places, so it's best that it's in the root directory.
10. Finally, in your includes/footer file, change the reference to your stylesheet to be ../style/style.css (we're going up one level since we're in the templates folder.).  Make sure your stylesheet link hasn't broken!
11. Sync your files back up to GitHub.

### Default Layout Template

<script src="https://gist.github.com/challahan/a96842301446e9eab594.js"></script>

### Default Frontmatter

<script src="https://gist.github.com/challahan/ffac402d02474ab67ade.js"></script>

## How to Turn In the Assignment

You'll be submitting your templates via your GitHub repository.

1.  Make sure your three templates are placed in the "templates" folder and that they are actively using Jekyll.
2.  On your root index.html file, which is the Project Hub, add an H2 with Date: Templates.
3.  Add a link to your three templates under the Templates section.  Name each link with the title of the template, for example "Product Page Template".
4.  After you've commited and synced your changes via GitHub Desktop, you can submit both the timeline hyperlink and the link your three templates via Blackboard Learn.  Note: Don't link to the local version on your computer.  You need to access the live version on the web with the GitHub.io URL.

## Rubric

Use the following rubric to ensure you receive the highest possible grade for the assignment:

* **8-10**: You've put everything you've learned so far together.  Your templates' HTML and CSS uses the appropriate content and styles.  Your templates form a cohesive whole, but also demonstrate a unified design system.  You'll successfully installed and are using Jekyll for any global or shared elements, such as the header and footer, so that content isn't repeated.  Your HTML is structured well, and you are using appropriate breakpoints in your CSS.
* **4-7**: You've put together the templates, but they don't always show a unified design system.  Some of the content is missing or not in appropriate places.  Jekyll may have been installed, but you're still repeating some shared components like the header and footer.  There are some issues with the responsive breakpoints - more testing may be needed on different sized screens.  There are also a few HTML and CSS errors.
* **0 - 3**: The design system for your templates is week and templates don't follow the structure of your content.  HTML and CSS structure is weak and doesn't follow what you've learned in class.  Jekyll wasn't installed correctly or the assignment instructions weren't followed fully.  A lot more work is required to make the templates ready for client review.