# RESPONSIVE WEB DESIGN and FLOATS #

## What is Responsive Web Design? ##
### Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones) ###

## What is the difference between Responsive and adaptive? ##
- Responsive generally means to react quickly and positively to any change, With responsive design websites continually and fluidly change based on different factors, such as viewport width.
- Adaptive means to be easily modified for a new purpose or situation, such as change. Adaptive websites are built to a group of preset factors.

## What are the three main components of Responsive web design? ##
- Flexible layouts, Media queries and Flexible media.

## Media Queries

With media queries you can define completely different styles for different browser sizes.
Example: resize the browser window to see that the three div elements below will display horizontally 
on large screens and stacked vertically on small screens. 

* Logical operators in media queries help build powerful expressions.

* Using the viewport meta tag with either the height or width values will define the height or width of the viewport respectively.


## flexible layout
approach to page layout attempts to accommodate the diversity of display environments. Rather than serving only the "most common" display dimensions and the "typical" user, a flexible layout adapts to different viewing conditions and different user requirements. Flexible layouts are far more difficult to design than fixed layouts because elements need to be able to change shape and position without jeopardizing the integrity of the overall page design.

## What is SMACSS?
####  is short for (Scalable and Modular Architecture for CSS) is a style guide that follows five simple categories and its a is a way to examine your design process and It is an attempt to document a consistent approach to site development when using CSS.

### Which are these categories?

#### Base — These are your defaults (html, body, h1, ul, etc)
#### Layout — These divide the page into major sections
#### Module — These are the reusable modular components of a design
#### State — These describe how things look when in a particular state (hidden or expanded, active/inactive)
#### Theme — These define things like a color scheme or typographic treatment across a site

## Float ##
* Float is a CSS positioning property. 
* Absolutely positioned page elements are removed from the flow of the webpage.
* Absolutely positioned page elements will not affect the position of other elements and other elements will not affect them, whether they touch each other or not.
* The float:Inherit will assume the float value from that elements parent element.
* Floats can be used to create entire web layouts.
* While floats can still be used for layout, these days, we have much stronger tools for creating layout on web pages. Namely, Flexbox and Grid. Floats are still useful to know about because they have some abilities entirely unique to them, which is all covered in this article.
* Float's sister property is clear. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. Again an illustration probably does more good than words do.
* If the parent element contained nothing but floated elements, the height of it would literally collapse to nothing.
* We fix collapse by clearing the float after the floated elements in the container but before the close of the container.




