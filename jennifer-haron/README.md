# Kilovolt Blog

**Author**: Jennifer Williams Piper and Haron Yunis

**Version**: 1.0.0

## Overview

This is a fun website containing a blog with icons and content that are appealing to the user, and easy to use, to  entice the user to come back regularly. It should also ensure that the user has a similar experience on desktop and mobile devices.

## Getting Started
Fork and clone the repo at: 
* https://github.com/codefellows-seattle-301d30/03-jquery-and-events

* add CSS files to style the content

* update the js files to display blog posts using the details below (see architecture)


## Architecture

Project uses HTML, CSS, JavaScript and Markdown.
Blog articles are stored as objects in the rawData array. They are appended to the DOM using jQuery traversal and setter methods in article.js.  Each article displays author, title, link to author page, time since publication, and blog entry. articleView.js contains code to populate author and category filters, and show or hide appropriate articles depending on user input.


## Change Log

02-15-2018 9:25am - Forked and cloned repo, initial setup by duplicating starter code, adding README, normalize.css

02-15-2018 10:10am - Added data-author attribute, called populateFilters method to add authors and categories to dropdown menus.

02-15-2018 11:05am - Finish handleAuthorFilter method, so articles by selected author fade in, and all articles fade in on reset.

02-15-2018 12:05pm - 	Finised handleCategoryFilter. Categories are now showing when choosen and the listener is working correctly.

02-15-2018 12:43pm = Finished handleMainNav function. To switch between tab content sections on user click. 
## Credits and Collaborations

* Source of normalize.css from github.com/necolas/normalize.css

* Icon fonts from IcoMoon: https://icomoon.io/
