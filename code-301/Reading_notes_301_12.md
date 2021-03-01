# EJS Partials

> ## What is  partials and why we use it ??
### partials it like reuse the same html across multiple views we use it to help us to make large website easyer.

### To use partials for example we need to use the navigation bar and the footer for all pages that we have, What we should do to apply that :
1. create new directory in views directory then create files foe navigation and footer and write our code that we need 
2. in your pages which you want to you the navigation bar and footer apply this tow fils .
3. By using this  <%- include( PARTIAL_FILE ) %> 
> ### Note: The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement.

### After that we should be able to see the navigation bar and footer in our pages thet we have linked it on.