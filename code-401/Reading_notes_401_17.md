# Spring Boot and OAuth2.

## In  this reed we will sammariz how to build a sample app doing various things with "social login" using OAuth 2.0 and Spring Boot.

### We haveseveral samples building on each other, adding new features at each step:*


* #### simple: using vary simple way to login when you go to the login page will direct you to outher page to login

    * ##### We have a features in Spring Boot called autoconfiguration that help us to  use single sign in.

    * ##### if we want to use github to sign in we need to add a new  new OAuth application for github  and add our home page.

    * ##### we need to add a yml file in our projct.

* #### click: explicit link that the user need to click to login 

    * #### we will modify the simple app you just built by adding an explicit link to login with GitHub. Instead of being redirected immediately.

    * #### 

* #### logout: if you are authenticated users you will see this a logout link.

    * ##### we just need to provide a logout button and some JavaScript to call back to the server to ask for the authentication to be cancelled
    * ##### also we need to add a endpoint after logout 

* #### two-providers: add two way to login 

* #### custom-error: show error massage for  unauthenticated users.
