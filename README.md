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

Utility Styles
1. Moved a, p, floats to new section in CSS called "utility styles."

Under Header
2. <div class="header"> changed to "header"
3. <div> holding nav elements renamed to "nav"
4. Renamed styles in .css from .header to header and from div to .nav.

Under Hero
1. Change <div> to <section> with a class of "hero" in HTML.

Under Content
1. Change <div> to <section> with a class of "online-marketing" in HTML.
2. Changed <div> from each sub-section into <article> for each with their existing classes in HTML.
3. Added meaningful "alt" tags to images
4. In CSS, moved all CSS having to do with Content section in between "Content" comments.
5. Condensing class names under this section to all be under class "online-marketing-types." Why? Because all class .css in this section are redundant.  Condensed "img," "h2" and type-specific formatting.
6.  Added id of "search-engine-optimization" to that section as link was broken.
