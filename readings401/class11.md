# Spring MVC

- Spring MVC calls the pieces of data that can be accessed during the execution of views model attributes.
- MVC stands for => Model View Controller.

![scanner](https://www.javatpoint.com/images/sp/mvc.jpg)

## How it works:
- Create a Web Controller
- create HTML page to show our data


## Spring MVC and Thymeleaf: how to access data from templates

### @Controller classes are responsible for preparing a model map with data and selecting a view to be rendered

1- Spring model attributes:
Add attribute to Model via its addAttribute method

2- Request parameters
Request parameters are passed from the client to server

3- Session attributes
add mySessionAttribute to session

4- ServletContext attributes
The ServletContext attributes are shared between requests and sessions. In order to access ServletContext attributes in Thymeleaf you can use the #servletContext.

5- Spring beans
Thymeleaf allows accessing beans registered at the Spring Application Context with the @beanName syntax.

