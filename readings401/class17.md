# Spring Boot and OAuth2

![scanner](https://www.baeldung.com/wp-content/uploads/2019/07/bael-1239-image-simple-1-950x700.png)


## What is Authorization?
- Authorization happens after a user’s identity has been successfully authenticated. 
- It is about offering full or partial access rights to resources like database, funds, and other critical information to get the job done.

## Popular authorization techniques 
- Role-based access controls (RBAC) can be implemented for system-to-system and user-to-system privilege management.
- JSON web token (JWT) is an open standard for securely transmitting data between parties, and users are authorized using a public/private key pair.
- SAML is a standard Single Sign-On format (SSO) where authentication information is exchanged through XML documents that are digitally signed.
- OpenID authorization verifies user identity based on an authorization server’s authentication.
- OAuth allows the API to authenticate and access the requested system or resource.

## There are several samples building on each other, adding new features at each step:
- simple: a very basic static app with just a home page and unconditional login via Spring Boot’s OAuth 2.0 configuration properties (if you visit the home page, you will be automatically redirected to GitHub).
- click: adds an explicit link that the user has to click to login.
- logout: adds a logout link as well for authenticated users.
- two-providers: adds a second login provider so the user can choose on the home page which one to use.
- custom-error: adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API.

