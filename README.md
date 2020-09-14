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
1. <title> changed text "Horiseon" in HTML.
 
Utility Styles
1. Moved <a>, <p>, to rest under <body> in CSS so "utilities" kept together.

Under Header
1. <div class="header"> changed to <header> in HTML.
2. <div> holding nav elements renamed to <nav> in HTML.
3. Renamed styles in CSS to correspond to those changes

Under Hero
1. Changed <div> to <section> with a class of "hero" in HTML.

Under Marketing Types
1. Changed <div> to <section> with a class of "online-marketing" in HTML.
2. Changed <div> from each sub-section into <article> for each with their existing classes in HTML.
3. Added meaningful "alt" tags to images, but no names because just icons.
4. In CSS, moved all CSS having to do with Marketing section in between "Marketing" comments.
5. Condensing class names under this section to all be under class "online-marketing-types." Why? Because all class .css in this section are redundant.  Condensed "img," "h2" and type-specific formatting.
6.  Added ID of "search-engine-optimization" to that section as link was broken.

Benefits
1.  Change first <div> to <section> in HTML
2.  Condense code in CSS
3.  Added "alt" tags to <img> and fixed Cost Management <img> tag. Left <alt> tags blank as icons just added for design.
4.  Changed second <div> tags in to <article>.
5.  Removed redundant classes and used just one .benefits-type.
6.  Moved color to .benefits in CSS.
7.  Condensed <H3> and <img> in CSS.

Footer
1. Change <div> to <footer>. Remove "footer" class and changed CSS to use "footer" instead of ".footer"adjusted CSS accordingly.

Post-Mortem
1. Looking for redundancies in code:
   Moved redundant mentions of "font-family" to <body>.
   Moved redundant mentions of "color" to <body>.
2. Fixed Color bug on Footer.