#Following The Odin Project Foundation Course path. Working on a css file labs.

##Project Journal (recent first)


###August 4, 2026
* **css-flex/layout-2**
    * Update CSS file link in HTML.
    * Fixed body behavior by switching from flex column to block layout.
    * Implement fixed positioning on sidebar to keep it locked to the left side column.
    * Implement fixed edge-to-edge layout for the bottom footer.
    * Convert cards into 250px squares that wrap fluidly across the available workspace.
    * Clean up default bullet formatting and underlines on sidebar links.

###August 3, 2026
* **css-flex/layout-1**
    * Update CSS file link in HTML.
    * Converted `body` into a flex column to pin the footer to the bottom.
    * Added Flexbox layout to `.header`, `.footer`, and `.content` containers.
    * Removed browser default list bullets, margins, and anchor lines.
    * Applied spacing, margins, and backgrounds to match the mockup.


###July 21, 2026
* **css-flex/information**
    * Update CSS file link in HTML.
    * Converted layout to flexbox grid using row wrapping.
    * Centered the main title horizontally across the page.
    * Set images and text to percentage-based flex widths.
    * Used flex order property to group images on top and text below.

###July 20, 2026
* **css-flex/header-2**
    * Fixed CSS file link in HTML.
    * Implemented Flexbox layout: aligned logo and navigation links to `flex-start`.
    * Utilized `margin-left: auto` to push the notifications button to the `flex-end`.


###July 17, 2026
* **css-flex/header**
    * Edited link for css on html
    * Added flexbox stretching the body across the page width using:
        * `flex-flow: row wrap`
        * `justify-content: space-evenly`
        * `flex-grow: 1`
        * `margin: 0`
    * Targeted `head, title` with `display: none !important` to hide leaked page metadata caused by the universal selector

###July 14, 2026
* **css-flex/center**
    * Added link for css on html
    * Added flexbox centering ('justify-content' and 'align-items')

###June 01, 2026
**Added**
- On 01-margin-padding.css:
    - On .three - added top, bottom, right on margin instead of just sticking with margin-left 
- On 02-margin-padding.css:
    - Universal selector with properties - margin, padding, font size
    - Padding on title selector
    - On button-container, a flex box, margin, padding
    - On button selector, an inline block display, margin, padding
**Edited**
- On 01-margin-padding.css:
    - Linked updated to match the css file
    - Changed the .one padding and margin
- On 02-margin-padding.css:
    - Moved font family to universal selector
**Note**
- On 01-margin-padding.css:
    - I didn't think I had to change anything .two as instructed


###May 29, 2026
**Added**
- New directories - restructure-repo and block-and-line
- 2 html and css files for block-and-line
**Edited**
- Created and moved html and css file of same name to appropriate directories
**Pending**
- Work on both 01 and 02 html and css files - for reference back on The Odin Project CSS class 5 github link.


###May 22, 2026
**Edited:**
- html file only to link to existing css file on local machine
- moved .para selector above .small-para selector
- added color and font weight property to .para selector
- added color only to .small-para
- .confirm changed to #confirm-button
- changed font weight from bold to 800 to #confirm-button for cleaner code
- .child changed to .text .text.child
- .text .text.child selector font size property changed from 14px to 16.5px
- div.text changed to .text selector
**Removed:** 
- .para, .small-para selectors