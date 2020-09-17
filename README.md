<h1>Code Refactoring of Horiseon Website</h1>

The following was a code refactoring of the code to more semantic HTML and concise CSS.  Classes and ID's were combined where possible and div's renamed to section, header, footer, etc where it made sense.  Alt's were added to the images; however, they were only filled in with an actual description if it made sense to name the image.  Three cases it did not makse sense as it didn't add any information to the page.

********************************************************<br />
View: https://webprinc3ss.github.io/horiseon-refactor/<br />
Screenshot: https://webprinc3ss.github.io/horiseon-refactor/horiseon-screenshot.jpg<br /><br />

<h2>Details of Changes Made</h2>
<br />
<b>Under Head</b><br />
1. TITLE changed text "Horiseon" in HTML.<br /><br />
 
<b>Utility Styles</b><br />
1. Moved A, P, to rest under BODY in CSS so "utilities" kept together.<br /><br />

<b>Under Header</b><br />
1. "div class="header"" changed to HEADER tag in HTML.<br />
2. DIV holding nav elements renamed to NAV in HTML.<br />
3. Renamed styles in CSS to correspond to those changes<br /><br />

<b>Under Hero</b><br />
1. Changed DIV to SECTION with a class of "hero" in HTML.<br /><br />

<b>Under Marketing Types</b><br />
1. Changed DIV to SECTION with a class of "online-marketing" in HTML.<br />
2. Changed DIV from each sub-section into ARTICLE for each with their existing classes in HTML.<br />
3. Added meaningful "alt" tags to images, but no names because just icons.<br />
4. In CSS, moved all CSS having to do with Marketing section in between "Marketing" comments.<br />
5. Condensing class names under this section to all be under class "online-marketing-types." Why? Because all class .css in this section are redundant.  Condensed IMG, H2 and type-specific formatting.<br />
6.  Added ID of "search-engine-optimization" to that section as link was broken.<br /><br />

<b>Benefits</b><br />
1.  Change first DIV to SECTION in HTML<br />
2.  Condense code in CSS<br />
3.  Added "alt" tags to IMG and fixed Cost Management IMB tag. Left ALT tags blank as icons just added for design.<br />
4.  Changed second DIV tags in to ARTICLE.<br />
5.  Removed redundant classes and used just one .benefits-type.<br />
6.  Moved color to .benefits in CSS.<br />
7.  Condensed H3 and IMG styles.<br /><br />

<b>Footer</b><br />
1. Change DIV to FOOTER. Remove "footer" class and changed CSS to use FOOTER instead of ".footer"adjusted CSS accordingly.<br /><br />

<b>Post-Mortem</b><br />
1. Looking for redundancies in code:<br />
   Moved redundant mentions of "font-family" to BODY.<br />
   Moved redundant mentions of "color" to BODY.<br />
2. Fixed Color bug on FOOTER.<br />