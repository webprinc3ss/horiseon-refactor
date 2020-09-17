<h1>Code Refactoring of Horiseon Website</h1>

The following was a code refactoring of the code to more semantic HTML and concise CSS.  Classes and ID's were combined where possible and div's renamed to section, header, footer, etc where it made sense.  Alt's were added to the images; however, they were only filled in with an actual description if it made sense to name the image.  Three cases it did not makse sense as it didn't add any information to the page.

********************************************************<br />
View: https://webprinc3ss.github.io/horiseon-refactor/<br />
Screenshot: https://webprinc3ss.github.io/horiseon-refactor/horiseon-screenshot.jpg<br /><br />

<h2>Details of Changes Made</h2>
   <br />
   <H3>Under Head</H3><br />
      <ol>
         <li>TITLE changed text "Horiseon" in HTML.
      </ol>
      <br />
 
   <H3>Utility Styles</h3>
      <br />
      <ol>
         <li>Moved A, P, to rest under BODY in CSS so "utilities" kept together.</li>
      </ol>
      <br />

   <H3>Under Header</h3>
      <ol>
         <li>"div class="header"" changed to HEADER tag in HTML.</li>
         <li>DIV holding nav elements renamed to NAV in HTML.</li>
         <li>Renamed styles in CSS to correspond to those changes</li>
      </ol>
      <br />

   <H3>Under Hero</h3>
      <ol>
         <li>Changed DIV to SECTION with a class of "hero" in HTML.</li>
      </ol>
      <br />

   <H3>Under Marketing Types</h3>
      <ol>
         <li>Changed DIV to SECTION with a class of "online-marketing" in HTML</li>
         <li>Changed DIV from each sub-section into ARTICLE for each with their existing classes in HTML.</li>
         <li>Added meaningful "alt" tags to images, but no names because just icons.</li>
         <li>In CSS, moved all CSS having to do with Marketing section in between "Marketing" comments.</li>
         <li>Condensing class names under this section to all be under class "online-marketing-types." Why? Because all class .css in this section are redundant.  Condensed IMG, H2 and type-specific formatting.</li>
         <li>Added ID of "search-engine-optimization" to that section as link was broken. </li>
      </ol>
      <br />

   <H3>Benefits</h3>
      <ol>
         <li>Change first DIV to SECTION in HTML</li>
         <li>Condense code in CSS</li>
         <li>Added "alt" tags to IMG and fixed Cost Management IMB tag. Left ALT tags blank as icons just added for design.</li>
         <li>Changed second DIV tags in to ARTICLE.</li>
         <li>Removed redundant classes and used just one .benefits-type.</li>
         <li>Moved color to .benefits in CSS.</li>
         <li>Condensed H3 and IMG styles.</li>
      </ol>
      <br />

   <H3>Footer</h3>
      <ol>
         <li>Change DIV to FOOTER. Remove "footer" class and changed CSS to use FOOTER instead of ".footer"adjusted CSS accordingly.</li>
      </ol>
      <br />

   <H3>Post-Mortem</h3>
      <ol>
         <li>Looking for redundancies in code:
            <ul>
               <li>Moved redundant mentions of "font-family" to BODY.</li>
               <li>Moved redundant mentions of "color" to BODY.</li>
            </ul>
         <li>Fixed Color bug on FOOTER.
      </ol>