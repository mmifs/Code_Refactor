# Code Refactor Finished Code

For my task on this project I was requested to do the following:

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

I took the provided source code and applied several changes

Total list of changes follow: 

- Added alt tags for imgs on index.html
- Added descriptive title element on index.html
- Removed ID tags from 2 content div sections (unused)
- Changed footer h element from h2 to h4 to reflect sequential order
- Added line breaks to make code more readible between different div sections
- Combined several sections on style.css to remove duplicate code