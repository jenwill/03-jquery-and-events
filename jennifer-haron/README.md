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

Project uses HTML, CSS, JavaScript and Markdown. This application is designed with mobile first in mind, and extra css code for desktop viewers, with a breakpoint at 640px. The mobile viewers, to maximize screen space, start with the dropdown menu hidden, and the menu becomes visible when the hamburger icon is hovered over. The desktop viewers do not see the hamburger icon, and can see the nav menu from the beginning.
A constructor function is used for the articles. Blog articles are stored as objects in the rawData array. They are appended to the DOM using jQuery traversal and setter methods. Each article displays author, title, link to author page, time since publication, and blog entry.


## Change Log

02-15-2018 9:25am - Forked and cloned repo, initial setup by duplicating starter code, adding README, normalize.css

02-15-2018 10:10am - Added data-author attribute, called populateFilters method to add authors and categories to dropdown menus.

02-15-2018 11:05am - Finish handleAuthorFilter method, so articles by selected author fade in, and all articles fade in on reset.

## Credits and Collaborations

* Source of normalize.css from github.com/necolas/normalize.css

* Icon fonts from IcoMoon: https://icomoon.io/
