# week-one-homework
Week One Homework: Code Refactor

## Project description
One of the main objectives of this code refactor is to consolidate the CSS elements from their redundant state to one that requires a great deal less code, but effects the same outcome. Another goal of this refactor is to ensure that all links on the site are functioning as intended. The final overarching objective is to ensure that all changes to the code in both the HTML and CSS files are properly and thoroughly notated while following industry standards.

## Changes made to index.html file:

1. Changed the page title section from "website" to "Horiseon Services Provided" as that is what the page appears to display/describe.
2. Added an id tag to line 31 for "search-engine-optimization" in order to have the link at the top of the page shift the page view to that section below (as the other 2 links do).
3. Changed the h3 tags found in the class=benefits section to h2 tags as they appeared to be at the same level of importance as the h2 tagged descriptors in the content section. Both sections included a basic header describing the information pertaining to that header below, I saw no reason for them to have different tiered h tags.
4. In keeping with Google's HTML indentation standards I indented all paragraph tags two spaces further than all header tags that they were associated with. 
    Above mentioned standards: <a href="https://developers.google.com/style/html-formatting">Google Indentation Standards</a>
5. Added alt text descriptions for all image files on this page to help identify them as well as their purpose/meaning if they do not load on the page and for visually impaired users.
6. Edited the HTML code that references the old classes to match the new one. (see CSS changes for more details)

## Changes made to style.css file:

1. Removed classes .benefit-lead, .benefit-brand, .benefit-cost and replaced them with a single .benefit-detail class. Edited the HTML code that references the old classes to match the new one.
2. Removed classes .search-engine-optimization, .online-reputation-management, .social-media-marketing and replaced them with a single .content-description class. Edited the HTML code that references the old classes to match the new one.

## Link to completed application:

https://micah41224.github.io/week-one-homework/

## Screenshots:

![Completed Application Screenshot](assets/screenshots/Final_Screenshot.png)
