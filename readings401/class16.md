# Spring Authentication
![scanner](https://docs.gigaspaces.com/attachment_files/SpringSecurity-ProviderManager.png)


- Spring Security: is a framework that focuses on providing both authentication and authorization to Java applications.

## Features
- Comprehensive and extensible support for both Authentication and Authorization
- Protection against attacks like session fixation, clickjacking, cross site request forgery, etc
- Servlet API integration
- Optional integration with Spring Web MVC

## Spring Auth Cheat Sheet:
- Step 1: set up a user model and repo
- Step 2: create a controller for that model
- Step 3: UserDetailsServiceImpl implements UserDetailsService
- Step 4: ApplicationUser implements UserDetails
- Step 5: WebSecurityConfig extends WebSecurityConfigurerAdapter
- Step 6: registration page
- Step 7: login page

