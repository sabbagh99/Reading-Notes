# Spring Authentication.

## Authentication and Authorization:

* ### Authentication :is the process of recognizing a user’s identity.

    * #### In authentication we will use `AuthenticationManager` interface method  and this methos have three  authentication methods `authentication()` which is back with a true vallue if the input represents a valid principal, `AuthenticationException` when the input represents an invalid principal and  `null` if it cannot decide.

* ### Authorization :is a security mechanism to determine access levels or user.

    * #### "An AccessDecisionVoter considers an Authentication (representing a principal) and a secure Object, which has been decorated with ConfigAttributes":

    * #### `ConfigAttributes`: this attributes supported by  AccessDecisionVoter that give if authenticated  or not and give the rule of the user.

* ### Web Security : when the client send a request to a application  the  container decides which filters and which servlet apply to it based on the path of the request URI.