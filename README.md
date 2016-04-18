# ColorCustomizer


#Instructions:

Implement a simple web application to display a user-entered color -- There should be at least two visible items on the page:

### [X] An input box

### [X] A div with a border (so you know it's there even when the color is the same as the page color). <em>Added dotted border line</em>

#### [X] The div should show whatever color the user supplies in the input dynamically ("purple", "#0f0", "#fff000", etc.). 

[X] Always display the latest valid color 
[X] Pressing enter in the input box should have no effect.
[X] The input box should initially prompt the user with something like "Enter a color or code".
[X] Feel free to extend the application any way you see fit, or talk about potential extensions.
[X] Use a modern Javascript MV* library like React, Backbone, Ember, Angular, etc. <em> used Angular</em>

## Extensions

### On-Hover color selection: This would replace the current text input field. User's cursor changes the background color on-hover over one of n selections in a colorgrid or colorwheel 

### Fancy iFrame of Inspiration: User's color selection results in secure iframe of inspiring open-source images in that tone (eg. http://labs.tineye.com/multicolr/#colors=638fc3;weights=100;) 

## Embedded Routing feature
### The user will click "<" and ">" link to advance through different input options rather than filling in the code or color. 
### A new input will appear as a nested
The first is above below the original div box.
### 

http://labs.tineye.com/multicolr/#colors=638fc3;weights=100;

## Technical Tweaks

### Factor lines 22-27 of Angular.js into an app.js file before adding new Angular features.

### Factor all custom CSS out of index.htmls and into custom.css file

### Verify functionality in IE 8 and Firefox 3.6, since Bootstrap has dropped support for these. If not responsive, polyfill.

## Design Tweaks

### Update Favicon from paintbrush/palette to color wheel or other modern design.

### Add color transition delay (fade-in/out) for smoothness of experience.

### Have a unicorn jump across the screen whenever the user changes the background...obviously.

