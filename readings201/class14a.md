# Class 14a reading Notes #

## CSS Transforms ##
- The transform property applies a 2D or 3D transformation to an element each of these come with their own individual properties and values. 
- This property allows us to rotate, scale, move, skew, etc., elements.

### Transform Syntax ###
transform: none|transform-functions|initial|inherit;

### CSS 2D Transforms Methods ###
- With the CSS transform property you can use the following 2D transformation methods:

* translate(),moves an element from its current position (according to the parameters given for the X-axis and the Y-axis).
* rotate(),rotates an element clockwise or counter-clockwise according to a given degree.
* scaleX(),increases or decreases the width of an element.
* scaleY(),increases or decreases the height of an element.
* scale(),increases or decreases the size of an element (according to the parameters given for the width and height).
* skewX(),skews an element along the X-axis by the given angle.
* skewY(),skews an element along the Y-axis by the given angle.
* skew(),skews an element along the X and Y-axis by the given angles.
* matrix(),combines all the 2D transform methods into one.

### CSS 3D Transforms ###
- With the CSS transform property you can use the following 3D transformation methods:

* rotateX(),rotates an element around its X-axis at a given degree.
* rotateY(),rotates an element around its Y-axis at a given degree
* rotateZ(),rotates an element around its Z-axis at a given degree

## CSS Transitions ##
- CSS transitions allows you to change property values smoothly, over a given duration.
 
### How to Use CSS Transitions? ###
- To create a transition effect, you must specify two things:
  * the CSS property you want to add an effect to
  * the duration of the effect
  * The transition effect will start when the specified CSS property (width) changes value.

###  Transition functions ###
- The transition-timing-function property can have the following values:
  * ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
  * linear - specifies a transition effect with the same speed from start to end
  * ease-in - specifies a transition effect with a slow start
  * ease-out - specifies a transition effect with a slow end
  * ease-in-out - specifies a transition effect with a slow start and end
  * cubic-bezier(n,n,n,n) - lets you define your own values in a cubic-bezier function
  
- The transition-delay property specifies a delay (in seconds) for the transition effect.

## CSS Animations ##
- CSS allows animation of HTML elements without using JavaScript or Flash!

### CSS Animations propirties ###
- @keyframes,When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.
- animation-name,Specifies the name of the @keyframes animation
- animation-duration, defines how long time an animation should take to complete
- animation-delay,specifies a delay for the start of an animation.
- animation-iteration-count,specifies the number of times an animation should run.
- animation-direction,specifies whether an animation should be played forwards, backwards or in alternate cycles.
- animation-timing-function,specifies the speed curve of the animation.
- animation-fill-mode,specifies a style for the target element when the animation is not playing (before it starts, after it ends, or both)
- animation,for setting all the animation properties






