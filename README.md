# TypeColourly
Colour based note-taking webapp
DATA FLOW:

User Input → Character Counter Update → Limit Enforcement

Color Selection → Text Color Change → Entry Color Preservation

Enter Key Press → Entry Creation → Display Update → State Reset

CUSTOMIZATION GUIDE:

To change default colors:

Modify data-color attributes in HTML

Update swatch background colors in style attributes

To modify visual styling:

Adjust CSS variables in style section

Modify container dimensions in .container class

Update color values in relevant CSS rules

To change default character limit:

Modify charLimit variable in JavaScript

Update initial counter text in HTML

BROWSER COMPATIBILITY:

Tested on modern browsers (Chrome, Firefox, Safari, Edge)

Uses standard ES6 JavaScript features

Relies on basic CSS Flexbox layout

ACCESSIBILITY NOTES:

Color swatches use distinct colors for color contrast

Counter has title attribute for discoverability

Textarea has clear placeholder text

Consider adding ARIA labels for screen readers

PERFORMANCE CONSIDERATIONS:

Uses efficient DOM query caching

Limits reflows with CSS transforms

Implements input debouncing implicitly

Uses lightweight event listeners

SECURITY CONSIDERATIONS:

Sanitizes user input through textContent

Uses parseInt with explicit base

Prevents XSS through automatic escaping

Limits maximum input length

ERROR HANDLING:

Gracefully handles invalid character limits

Prevents empty entries from being saved

Maintains valid state after invalid limit edits

Preserves existing content when trimming

FUTURE ENHANCEMENTS:

Add local storage persistence

Implement multiple color palettes

Add text formatting options

Include entry deletion functionality

Add export/import capabilities

DEPENDENCIES:

Modern web browser with ES6 support

Internet connection (for CDN fonts if used)

No external libraries required

VERSION HISTORY:
1.0.0 - Initial release with core functionality

Character counter with configurable limit

Basic color palette implementation

Entry saving system

Responsive layout design
