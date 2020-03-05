# reformatting-accessibility-seo-friendly

Some basic refactoring of a marketing agencies web page to increase readability, accessibility, and search engine optimization.

## The Goal

Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## Steps Taken

- Looked for any repeating css and condensed classes accordingly. Was able to reduce the css by about 80 lines.
- Added comments to describe the main areas of the HTML and CSS
- Noticed a lot of div usage and utilized the header, section, main, and footer tags in place of div's where appropriate
- Added alt tags to each image
- Moved the large image from css to html using an img tag for better code readability
- Fixed a broken menu scroll by adding a missing id to the associated content
- Added meta description and viewport for SEO purposes, also added a descriptive title
- Renamed css classes to describe what they do with the next programmer in mind
- I read that rem is more accessible than px for fonts so i converted all font-sizes to rem.

## Stylistic Changes

- Made the padding consistent for the content areas. The services area had 50px and the benefits area had 20px. I upped benefits to 50px to be more consistent
- Increased the width of the benefits section to get a consistent gap between the content

## Screenshot

<img src="./assets/images/screenshot-of-page.PNG" alt="screenshot of webpage" width="500"/>

## Testing

I ran the webpage through some free accessability and seo tests that i found online that aided me in what to change. After my changes the webpage was able to recieve passing scores in each test. Here are some of the tests i used.

- https://achecker.ca/checker/index.php
- https://www.seobility.net/en/seocheck/
- https://neilpatel.com/seo-analyzer/
