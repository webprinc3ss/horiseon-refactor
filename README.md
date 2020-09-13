# Code Refactor Starter Code

Challenge Assignment

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

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

********************************************************

CHANGES MADE

Under Head
1. <title> tag changed text "Horiseon"

Under Header
2. <div class="header"> changed to "header"
3. <div> holding nav elements renamed to "nav"
4. Renamed styles in .css from .header to header and from div to .nav.

Under Hero
