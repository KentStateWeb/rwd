---
layout: wide
title: Creating Fields, Sections and Templates with Craft CMS
---

***Before Starting: Make sure that MAMP Pro is started and Craft has been set up the first time.  See [this article](craft.html) for more information.***

----

## Step 1: Plan out sections and fields

* Break up the pieces of the section/page you’re working on into fields
* Think about whether fields will be used in other sections or unique to this section
* A section doesn’t necessarily indicate a navigation item, but is representative of a type of content

----

## Step 2: Create Sections, Globals and Fields

### Sections

Sections hold single pages and types of content on your site.  

1. Go to settings > sections > new section
2. Give section a name (i.e. Statistics).  The handle (how you reference the section in your templates) will automatically be created from the name.  You’ll need to reference this handle later, so note it.
3. Choose a section type

Single - is a single landing page (i.e. home page or about page)
Channel - a repeatable set of items (i.e. news articles, media partners, statistics)
Structure - rarely used, only when channel items must be displayed in a hierarchy

4.  Check if each entry should have its own URL. For example, if you wanted to show each new article on its own page, each should have its own URL. However, if you only wanted to show each statistic as a group together each would not need its own URL.
5.  Leave rest of the fields at their defaults

### Globals

Globals are sets of fields that are accessible across the entire website - for example, information stored in the header or footer.

1. Go to Settings > Globals > New global set
2. Enter a name and handle for the field
3. Click Save

----

## Step 3: Create the fields

***IMPORTANT:  The Title field is automatically created.***

Each field you planned out in step 1 needs to be created. However, if the field on the appropriate type and name already exists, you can simply reuse it.

1. Go to settings > fields > new field
2. Give the field a name.
3. Provide any instructions.
4. Choose the field type:

* Plain text - Unformatted text
* Assets - Any uploaded file. Including images, documents, files, and videos (you need to add an asset source the first time, or if you’d like to have your assets stored in a specific folder.  See below on Adding Asset Sources).
* Categories - Used to associate content with a taxonomy (i.e. For media partners we may categorize them by print, digital, or television.)
* Checkboxes - Choose from a list of items
* Entries - Associate one entry with another (i.e. link to an existing new story)
* Matrix - Mix several fields together and allow reordering of those fields
* Number - Only allow numerical values
* Rich text - Formatted text
* Table - Provide information in a row/column format

Optionally: You can group fields together by choosing “New group”

### Adding a New Source Folder for Assets Fields

1. Go to settings > Assets > New asset source
2. Give the asset a Name
3. Enter the File System Path: assets/img/YOURCHOICE
4. Enter the URL: {baseUrl}/assets/img/YOURCHOICE
5. Important - you must create the folder you just specified above in your assets/img folder on your local computer before it will work.

----

## Step 4: Add fields

### Sections

1. Go to sections > Edit entry type (for desired section) > Section name
2. Click the New tab
3. Drag the appropriate fields into the tab (Title is included by default)
4. Save

### Globals

1. Go to Settings > Globals
2. Click the Field Layout tab
3. Click new tab
4. Drag the appropriate fields into the tab
5. Save

----

## Step 5: Add content to your entries

The sections you created need content in them in order to display.  Each piece of content is called an entry in Craft.

1. Go to Entries > new entry > entry name (i.e. Statistics)
2. Fill in the content
3. Click save
4. Repeat for additional items related to this section (i.e. All 10 media partners)

----

## Step 6: Create template code

1. Open repository folder in your code editor (i.e. Atom)
2. Open the craft > templates folder
3. Choose which page(s) you want the items to display on.

* If they’re displaying only on the home page, open index.html (in the root folder).
* If they're displaying on all pages (i.e. Global fields), open _layout.html.
* If they’re displaying on one of the navigation items, choose the appropriate folder (i.e. Media outlets).
* If they’re displaying on their own individual page, create a new folder and title it the same as your section handle (i.e. statistics).
* If you created a new folder, create a new file inside the new folder and call it index.html.

Ensure the file includes:

{% highlight twig %}
{% raw %}
{% extends “_layout” %}
	{% block content %}
{% for entry in craft.entries.section(‘SECTIONHANDLE’) %}
	// YOUR FIELDS CODE GOES INSIDE HERE //
{% endfor %}
{% endblock %}
{% endraw %}
{% endhighlight %}

4. Add the below field code into your template in between the ‘for’ tags
5. Surround the fields with the appropriate html tags as needed.

### Plain text field/ rich text

{% highlight twig %}
{% raw %}
 {{ entry.FIELDHANDLE }}
{% endraw %}
{% endhighlight %}

i.e for the title field it would be {{ entry.title }}

### Image field

{% highlight twig %}
{% raw %}
{% for asset in entry.FIELDHANDLE %}
	<img src=”{{asset.url}}” alt=”{{asset.title}}”” />
{% endfor %}
{% endraw %}
{% endhighlight %}

### Entries field

{% highlight twig %}
{% raw %}
{% for entry in entry.FIELDHANDLE %}
	<a href="{{entry.url}}>"{{ entry.title }}</a>
{% endfor %}
{% endraw %}
{% endhighlight %}


----

## Step 7: Test in the browser and commit to GitHub with Tower

1. Go to http://studentmedia.web/DIRECTORYNAME (i.e. studentmedia.web/statistics)
2. If everything is displaced on your page, you’re ready to commit your changes
3. Open tower and commit any changed files
4. Click push

----

## Step 8: Test and production web site

***Important - Fields and sections do not sync between local and production environments, while changes to files and folders outside of Craft (such as templates folder) do.***  

1. Recreate the section, fields, and entries exactly as you did in your local environment
2. Go to http://kentstatestudentmedia.com/DIRECTORYNAME
3. Make sure everything is displaying correctly. If so, you’re done.
