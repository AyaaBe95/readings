# Components #

## EJS partial ##

- Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.
- We use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.

**The  syntax**

### <%- include('partials/partial') %>

for EX :
Under the views/partials/ directory create a file called **navbar.ejs** which will contain only the HTML for the navigation bar at the top of the home and post pages:



