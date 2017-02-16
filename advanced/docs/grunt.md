---
layout: wide
title: Pattern Lab, SASS and Grunt
---

The Grunt utility will allow us to quickly compile Pattern Lab patterns, SASS, JavaScript automatically through a single command.  It's required to get SASS files and Pattern Lab patterns to appear in the browser.

---

## Installing Grunt and Node the First Time

1.  Install Node.js for your OS [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
2.  Open the command line interface (called Terminal on the Mac)
3.  Type "sudo gem install sass" and enter
4.  Type "sudo npm install -g grunt-cli" and enter
5.  Navigate to the directory where your project is located.  If your project is located in the Documents folder on your computer, you would type: "cd Documents/studentmedia/httpdocs" and enter.
6.  Type "sudo npm install" and enter
7.  Type "grunt" and hit enter.

---

## Starting Up Grunt Again

Pattern Lab will build files every time you save them.  However, if you've exited the Terminal app, you'll need to do the following first:

1.  Open the command line interface (called Terminal on the Mac)
2.  Navigate to the directory where your project is located.  If your project is located in the Documents folder on your computer, you would type: "cd Documents/studentmedia/httpdocs" and enter.
3.  Type "grunt" and hit enter.

Grunt will stay running as long as you keep the terminal window open.  

To end Grunt, use Control + C.

---

## Adding Patterns to Pattern Lab

The full documentation for Pattern Lab is located at [http://patternlab.io](http://patternlab.io).

Here's the basics though:

1.  Pattern Lab lives in httpdocs/lab.  
2.  The individual patterns you'll edit live in httpdocs/lab/source.  You probably don't need to touch any of the other folders except in specific cases.
3.  In the source folder, there is a folder called "_patterns" which contains all of your individual patterns folder, organized into sections.  These folders make up the navigation in Pattern Lab.
4.  As you add a folder and files into the "_patterns", Grunt should compile the files and refresh the browser window automatically.  If it does not, you may need to re-save an existing file (a bug with auto refresh).
5.  The actual HTML code for each patterns goes in a file called FILE.mustache.  For example, header.mustache.  
6.  You can include patterns within other patterns!  Use {{> foldername-patternname}}.  For example, if my header pattern is in the Organisms folder, I would use {{>organisms-header}}
7.  You can also call data variables instead of hard coding data.  Data files are in the "_data" folder and can be called using {{ jsonvalue }}.

Use the full Pattern Lab documentation for more details.

<a href="/advanced" class="button small">Return to Class</a>
