# Refactoring_project

Horiseon Social Solution Services

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## Mock-Up

The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png)

> **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size.

Git Repository and README.md were created. Git add, commit, and push were completed frequently.Title was changed from website to Horiseon Social Solution Services. All link's are functioning correctly, selectors and properties are consolidated and organised to semantic structure. Comments are added to html and css and loads with no errors, better following conventions and identifications. Please find a link to deployed application here and a screen shot of the website.

![This is the screen shot of the web application.](./assets/Horiseon Social Solution Services.png)


CHANGES MADE

Changed all semantics from div to;
header
nav
img
main
section
aside
footer

Nav bar button "search engine optimization" wasn't linking to respective section until id and class were added to the correct section.
    Removed class and added them as alt attributes.

Element nav was updated in CSS so respective list are referenced correctly.

Adding img reference link including height and width, replaced that of the hero class in CSS.
    Returned height and width to CSS.
    Changed height and width to 100%.

Following CSS, class content was moved to follow the html placement.

Correctly linked the section ID's referenced from nav to respective CSS upon correct placement of elements.

Added accessability attributes

Consolidations in CSS were made to 
Main sections elements
Main images
Added sect1 and sect2 classes to consolidate h2 and h3
Aside text boxes
Aside images

