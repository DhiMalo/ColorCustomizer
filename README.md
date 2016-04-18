# ColorCustomizer

A simple web application to display a user-entered color 

1. [X] Input box
1. [X] Div with a border (so you know it's there even when the color is the same as the page color). <em>Added dotted border line</em>
1. [X] The div shows whatever color the user supplies in the input dynamically ("purple", "#0f0", "#fff000", etc.). 
1. [X] Always display the latest valid color 
1. [X] Pressing enter in the input box should have no effect.
1. [X] The input box should initially prompt the user with something like "Enter a color or code".
1. [X] Feel free to extend the application any way you see fit, or talk about potential extensions.
1. [X] Use a modern Javascript MV* library like React, Backbone, Ember, Angular, etc. <em> used Angular</em>

## Feature Extensions!

1. On-Hover color selection: This will replace the current text input field. User's cursor changes the background color on-hover over one of 'n' selections in a color wheel! 
1. Portal of Inspiration: User's color selection results in display of open-source images in given hue (see: http://labs.tineye.com/multicolr/#colors=638fc3;weights=100;) through an embedded viewport. 
1. Embedded Routing: Users will click "<" and ">" links to advance through alternative input options (vice filling in the code or color) - grid of color names, hex values.
1. Drag-and-drop: User can drag and drop color selections for different parts of the page (eg. first quote block becomes one color, next quote is another).  
1. Gamification: Continuous runner where user jumps to select desired color. 

## Technical Tweaks

1. Factor lines of Angular.js into an app.js file before adding new Angular features.
1. Factor all custom CSS out of index.htmls and into custom.css file
1. Verify functionality in IE 8 and Firefox 3.6, since Bootstrap has dropped support for these. If not responsive, polyfill.

## Design Tweaks

1. Add a color transition delay (fade-in/out) for smoothness of experience.
1. Update Favicon from paintbrush/palette to color wheel or other modern design.
1. Consider making some unicorns jump across the screen for Pete's sake. They do love rainbows.
