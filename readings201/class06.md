# Class-06 reading notes #

 ## WHAT IS AN OBJECT? ##
- Objects group together a set of variables and functions to create a model of a something you would recognize from the real world.

  ![Structure1](https://mathiasbynens.be/_img/js-engines/object-model.svg)
  
 ## In JavaScript: ##
* Variables have a name and you can assign them a value of a string, number, or Boolean.
*  Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.)
*  Named functions have a name and value that is a set of statements to run if the function is called.
*  Objects consist of a set of name/value pairs (but the names are referred to as keys).

 ## Document object models ##
- The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
> When a web page is loaded, the browser creates a Document Object Model of the page.

 ### The HTML DOM model is constructed as a tree of Objects: ###

  ![Structure2](https://www.w3schools.com/js/pic_htmltree.gif)
  
 - With the object model, JavaScript gets all the power it needs to create dynamic HTML:

* JavaScript can change all the HTML elements in the page
* JavaScript can change all the HTML attributes in the page
* JavaScript can change all the CSS styles in the page
* JavaScript can remove existing HTML elements and attributes
* JavaScript can add new HTML elements and attributes
* JavaScript can react to all existing HTML events in the page
* JavaScript can create new HTML events in the page
