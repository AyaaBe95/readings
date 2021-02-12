# Class-04 reading Notes #

# Links #
- Links are found in nearly all web pages. Links allow users to click their way from page to page.

### How we create links? ### 
- Links are created using the < a > element. Users can click on anything between the opening < a > tag and the closing < /a > tag. You specify which page you want to link to using the href attribute.

 * When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.
 * On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.
  ![Structure1](https://docs.jboss.org/jbossas/guides/installguide/r1/en/html/images/jboss_directory_structure.jpg)
  

## Relative URLs ##
 - Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
 
## Email Links , How we create it ? ##
 - To create a link that starts up the user's email program and addresses an email to a specified email address, you use the < a > element.
 - However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
 
## Opening Links in a New Window ##
 - If you want a link to open in a new window, you can use the target attribute on the opening < a > tag. The value of this attribute should be _blank.
 
# Layout #
- CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
- CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
- To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed.

# Screen Sizes #
- Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

# Screen Resolution #
- Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

# Functions,methods and objects #

## What is functions? ##
 - Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).
 
## How we create functions> ##
 - give it a name.
 - write the statements needed to achieve its task inside the curly braces.
 
## How we call the function? ##
- execute all of the statements between its curly braces with just one line of code.

## VARIABLE SCOPE ##
The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function.
 - LOCAL VARIABLES:When a variable is created inside a function using the var keyword, it can only be used in that function.
 - GLOBAL VARIABLES: If you create a variable outside of a function, then it can be used anywhere within the script.
