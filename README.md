Challenge Assignment<br /><br />

AS A marketing agency<br />
I WANT a codebase that follows accessibility standards<br />
SO THAT our own site is optimized for search engines<br />

GIVEN a webpage meets accessibility standards<br />
WHEN I view the source code<br />
THEN I find semantic HTML elements<br />
WHEN I view the structure of the HTML elements<br />
THEN I find that the elements follow a logical structure independent of styling and positioning<br />
WHEN I view the image elements<br />
THEN I find accessible alt attributes<br />
WHEN I view the heading attributes<br />
THEN they fall in sequential order<br />
WHEN I view the title element<br />
THEN I find a concise, descriptive title<br /><br />

********************************************************<br />
View: https://webprinc3ss.github.io/horiseon-refactor/<br />
Screenshot: https://webprinc3ss.github.io/horiseon-refactor/horiseon-screenshot.jpg<br /><br />

CHANGES MADE<br />
<br />
Under Head<br />
1. TITLE changed text "Horiseon" in HTML.<br /><br />
 
Utility Styles<br />
1. Moved A, P, to rest under BODY in CSS so "utilities" kept together.<br /><br />

Under Header<br />
1. "div class="header"" changed to HEADER tag in HTML.<br />
2. DIV holding nav elements renamed to NAV in HTML.<br />
3. Renamed styles in CSS to correspond to those changes<br /><br />

Under Hero<br />
1. Changed DIV to SECTION with a class of "hero" in HTML.<br /><br />

Under Marketing Types<br />
1. Changed DIV to SECTION with a class of "online-marketing" in HTML.<br />
2. Changed DIV from each sub-section into ARTICLE for each with their existing classes in HTML.<br />
3. Added meaningful "alt" tags to images, but no names because just icons.<br />
4. In CSS, moved all CSS having to do with Marketing section in between "Marketing" comments.<br />
5. Condensing class names under this section to all be under class "online-marketing-types." Why? Because all class .css in this section are redundant.  Condensed IMG, H2 and type-specific formatting.<br />
6.  Added ID of "search-engine-optimization" to that section as link was broken.<br /><br />

Benefits<br />
1.  Change first DIV to SECTION in HTML<br />
2.  Condense code in CSS<br />
3.  Added "alt" tags to IMG and fixed Cost Management IMB tag. Left ALT tags blank as icons just added for design.<br />
4.  Changed second DIV tags in to ARTICLE.<br />
5.  Removed redundant classes and used just one .benefits-type.<br />
6.  Moved color to .benefits in CSS.<br />
7.  Condensed H3 and IMG styles.<br /><br />

Footer<br />
1. Change DIV to FOOTER. Remove "footer" class and changed CSS to use FOOTER instead of ".footer"adjusted CSS accordingly.<br /><br />

Post-Mortem<br />
1. Looking for redundancies in code:<br />
   Moved redundant mentions of "font-family" to BODY.<br />
   Moved redundant mentions of "color" to BODY.<br />
2. Fixed Color bug on FOOTER.<br />