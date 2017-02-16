---
layout: wide
title: Setting up Craft + MAMP Pro
---

MAMP Pro allows you to run a PHP/MySQL-based CMS from your local computer.  Here's how to set it up:

## Install and Configure MAMP Pro the First Time

1.  Install MAMP Pro http://mamp.info
2.  Under ports - click the button to Set server ports to 80, 81, etc.
3.  Click the plus button underneath the box where "localhost" is listed
4.  Set up a new host directory (aka studentmedia.web) and point to the "httpdocs" folder instead of the root
5.  Set up a local database as well using "studentmedia_craft" as the database name.
6.  Set the default password for MySQL to "root"
7.  Start Servers by clicking the start button in the top Right of MAMP.  

Note:  MAMP Pro Must be running in order to access your site on your local computer.

## Set up Craft CMS

1.  Duplicate the craft/config/db-default.php file and call it db.php.  Edit it to include the LOCAL database name (assuming the password and user name are root).
2.  Go to the local URL on your computer to install Craft (aka http://studentmedia.web).  Go through the installation process.

## Editing Craft CMS Template Files

1.  Craft CMS template files are located in studentmedia/craft/templates.  You can organize these however you want, but the main template is "_layout.html".
2.  The CSS/SCSS, Images and JavaScript related to the CMS are in a different directory.  That directory is studentmedia/httpdocs/assets.
3.  Pattern Lab and Craft CMS share the same assets, so they'll automatically be in sync (yay).
