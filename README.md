# Project 0

Web Programming with Python and JavaScript (CSCI-S-33a)

Erik Subatis 7/2/2018

I decided to make a website mostly about our beloved dog Kenny, who takes himself very seriously. The website showcases
his company, services, and describes the board of directors behind the scenes. There are 6 pages total; a homepage, four
"sub" pages, and a landing page after filling out the contact form (note that the contact form doesn't actually submit an
email since we haven't covered that yet and it didn't appear there was a great way of doing this without JavaScript!).
The site leverages bootstrap heavily and every page is organized in bootstrap's grid (rows/columns). Everything is styled
in a single CSS file that is compiled from a single SCSS file.

Files:
index.html - The homepage, the bulk of which contains 3 jumbotron Bootstrap components
services.html - A description of Kenny's offered services, which contains a thumbnail Bootstrap component + 2 subsequent rows
pricing.html - Kenny's service pricing, organized into a standard HTML table
about.html - Kenny plus the 'board of directors', organized using Bootstrap media object components
contact.html - A (non-actually-functioning) contact form using Bootstrap-inspired forms/buttons
contact_landing.html - Landing page from contact.html, essentially just text
styles.scss - All pages are styled from here
styles.css - Compiled from styles.scss
images folder - Contains all images used on the site
*All pages contain the 'header' (image, logo, and nav menu) and 'footer' (text-based navigation and 'copyright')

Project Reqs (this was mostly a checklist for my own sake):
-6 HTML pages all accessible from another
-Unordered list: services.html, lines 102-107
-Table: pricing.html, lines 59-95
-Image: on all pages
-Stylesheets: styles.scss (code) / styles.css (compiled)
-5 CSS properties: in styles.scss,
-->background-color
-->border-radius
-->font-family
-->width & height
-->padding & margin, and others
-5 CSS selectors: in styles.scss,
-->many .class selectors
-->multiple #id selectors
-->multiple element selectors (ex. table, lines 64-89)
-->by attribute [role=button], lines 145-155
-->by pseudoclass hover, lines 168, 186, possibly others
-@media queries to resize images, styles.scss lines 104-134
-Bootstrap components: nav menu, jumbotron, thumbnails, media object, buttons
-Bootstrap grid/columns on all pages
-SCSS variables defined at top of styles.scss, used throughout
-SCSS nesting used for pricing table in styles.scss, lines 74-89
-SCSS inheritance used to define a %std-element near top of styles.scss, used for pricing-row, page-element

SOURCES:
Mostly used the Bootstrap documentation for things like:
-The starter template
-Components
-Help with rows/columns
-Utility classes

Used the !important tag to override the nav color; not sure if this is the best approach but got this from
https://stackoverflow.com/questions/46499994/how-to-change-the-default-navbar-background-color
