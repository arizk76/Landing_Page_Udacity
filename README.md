# Landing page project

A multi-sections landing page (dynamic nav bar menus and sections)

## Table of contents

1. Overview
2. Project requirements
3. Development workflow
4. Challenges and fix

### Overview

This project aims to simulate scenarios of manipulating the DOM using HTML, CSS and JavaScript Only.

The main targets from this landing page are:

- Appending dynamically added data to the DOM
- Show how javascript can improve the usability of an otherwise static site.

### Project requirements

Building a multi-section landing page by dynamically add the content to the page, navigation menu links and related sections should be added dynamically

To improve the user experience, the section actively being viewed should be differentiated in some way. Additionally, when a user clicks on a navigation item, the item should scroll to the appropriate section rather than giving the default browser jump behavior.

The project should have a structure like the one shown below:
css

- styles.css  
  index.html
  js
- app.js
  README.md

There are at least 4 sections that have been added to the page.

### Development workflow

The following steps are illustrating my development stages and my own strategy initially used for the landing page project:

1. Build static HTML first with 4 sections and 4 links.

Start by building a static HTML formatted using the following structure:

- Header at the top of page where dynamic nav menu will be added
- Hero section will be representing any landing page hero first look at.
- Sections container where dynamic sections will be added
- Footer at the bottom of the page.

2. Add styles to be responsive for screen types (small, medium and large).
3. Implement JavaScript for responsive part and section scroll.
4. Replace static Nav menu and sections with dynamic data.
5. Make necessary changes for dynamic DOM manipulation.
6. Test code in all possible scenarios.
