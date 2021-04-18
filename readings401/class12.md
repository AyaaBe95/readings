# Spring RESTful Routing & Static Files

![scanner](https://i2.wp.com/springframework.guru/wp-content/uploads/2017/09/mvc.png)


## @RequestMapping Basics

### @RequestMapping — by Path
 - define the Request URI to access the REST Endpoints
 - @RequestMapping(value = "/ex/foos", method = RequestMethod.GET)

### @RequestMapping — the HTTP Method
 - The HTTP method parameter has no default
 - @RequestMapping(value = "/ex/foos", method = POST)
  @ResponseBody
  
## RequestMapping and HTTP Headers

### @RequestMapping With the headers Attribute
- The mapping can be narrowed even further by specifying a header for the request:
- @RequestMapping(value = "/ex/foos", headers = "key=val", method = GET)
 @ResponseBody
 
### @RequestMapping Consumes and Produce
 - @RequestMapping(
  value = "/ex/foos", 
  method = GET, 
  headers = "Accept=application/json")
  @ResponseBody

###  RequestMapping With Path Variables
- Parts of the mapping URI can be bound to variables via the @PathVariable annotation.
- Single @PathVariable
- Multiple @PathVariable
- @PathVariable With Regex

### RequestMapping With Request Parameters
- allows easy mapping of URL parameters with the @RequestParam annotation.

### RequestMapping Corner Cases
 - @RequestMapping — Multiple Paths Mapped to the Same Controller Method :is usually used for a single controller method

### @RequestMapping — Multiple HTTP Request Methods to the Same Controller Method
 - Multiple requests using different HTTP verbs can be mapped to the same controller method.

### @RequestMapping — a Fallback for All Requests
 - to implement a simple fallback for all requests using a particular HTTP method
### Ambiguous Mapping Error 
 - The ambiguous mapping error occurs when Spring evaluates two or more request mappings to be the same for different controller methods. A request mapping is the same when it has the same HTTP method, URL, parameters, headers, and media type.


   

