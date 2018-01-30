---
layout: wide
title: Step 2 - Setting up Craft and Prototyping
---

MAMP Pro allows you to run a PHP/MySQL-based CMS from your local computer.  Here's how to set it up:

## Install and Configure MAMP Pro the First Time

1.  Install MAMP Pro http://mamp.info
2.  Under ports - click the button to Set server ports to 80, 81, etc.
3.  Click the plus button underneath the box where "localhost" is listed
4.  Set up a new host directory (aka PROJECTNAME.web) and point to the "httpdocs" folder instead of the root
5.  Set up a local database as well using "PROJECTNAME_craft" as the database name.
6.  Set the default password for MySQL to "root"
7.  Start Servers by clicking the start button in the top Right of MAMP.  

Note:  MAMP Pro Must be running in order to access your site on your local computer.

## Set up Craft CMS

1.  Duplicate the craft/config/db-default.php file and call it db.php.  Edit it to include the LOCAL database name (assuming the password and user name are root).
2. Important - change the public/htaccess file to be .htaccess.  
3. In craft/config/general.php - change the LOCAL url to your actual local URL. (in two places)
4. Go to the local URL on your computer to install Craft (aka http://PROJECTNAME.web).  Go through the installation process.

## Editing Craft CMS Template Files

1.  Craft CMS template files are located in PROJECTNAME/craft/templates.  You can organize these however you want, but the main template is layout.html.
2.  The CSS/SCSS, Images and JavaScript related to the CMS are in a different directory.  That directory is PROJECTNAME/httpdocs/assets.
3.  Pattern Lab and Craft CMS share the same assets, so they'll automatically be in sync (yay).

For more information about how to build Craft templates and fields, see [this article](craft2.html).


## Adding Patterns for Prototyping

There is a subfolder in your httpdocs folder called "lab".  This is where you can place webpages and components before they're ready for Craft CMS.

1.  Add a new pattern to the patterns folder by copying the "sample.php" file.  
2.  Add the pattern to the collective pattern page by including the PHP file in lab/patterns/index.php.
3.  Add your patterns to the pages by copying the "copyme" folder.  Include your patterns on "index.php" inside each of the folders.
4.  Finally, you can link to your pages in the lab/index.php file.
