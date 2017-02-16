---
layout: wide
title: Tower + GitHub
---

Tower (which syncs with GitHub) allows you to commit and push changes to the files on your local computer to the GitHub repository, which is where all of the project files live.

Tower does NOT sync database changes.  Database changes include content you add within Craft CMS like fields, content, images, sections and configuration options.  That means these have to be replicated by hand in production (yuck!).

## Setting up Tower the First Time

1.  Install Tower https://www.git-tower.com
2.  Enter your personal GitHub credentials when setting up (use Authentication Basic Auth!)
3.  Click the Cloud icon in the top left
4.  Choose your user account in the sidebar and then click Clone on the "studentmedia" repository.
5.  Choose a folder on your computer to clone the repository to.  You cannot change this directory later, so make a note of it.
6.  Once cloning has finished, all of the files will be on your local computer for editing.

## Syncing Changes with Push/Pull

Here's the process you should follow every time you start editing files on your computer:

1.  First, go into Tower and click PULL to get the latest changes from the server (assuming you haven't already edited your files).  This will help you avoid Merge Conflicts by ensuring you're up-to-date before starting work.  You cannot Push or Pull while there are files waiting to be committed in your Working Copy.  This area must be completely empty or you'll get a message about "Stashing" your changes.  Commit the changes first before Pushing or Pulling to avoid this message.
2.  Next, start editing your files.  As you edit files, they will begin to populate under the "Working Copy" showing your changes.  
3.  When you're ready to commit those changes, checkmark the files you're ready to commit or use the "Stage All" button to do all of them.
4.  Type in a Commit Subject and click the Commit button.
5.  You're not done yet!  You'll see beside "master" there will be a number corresponding to the number of commits you've made.  You need to click Push and then Push HEAD to actually commit the changes to the server.
6.  It will take up to 5 minutes for your changes to go live at the production website: www.kentstatestudentmedia.com.

## Resolving Merge Conflicts

Occasionally you will get a Merge Conflict when attempting to Pull files.  That means that one or more files has been edited by both you and another person.  Tower isn't sure which one is the most up-to-date version.

Thankfully, Tower makes this easy to resolve.

1.  Scan the list of files to find the one with the red "C" icon.
2.  On the right panel, after highlighting this file, Tower will show you both versions and ask you to choose one or the other.
3.  Once you've carefully chosen a version of the file, you will then have to Commit everything again.  This is called "merging" in Git.
