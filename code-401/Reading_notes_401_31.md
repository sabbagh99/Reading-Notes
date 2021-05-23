# A) Espresso

## We will use espresso to write concise, beautiful, and reliable Android UI tests.

### 1.  Synchronization capabilities : 

#### every time espresso test will invokes onView() and then we will wait  to perform corresponding UI action or assertion and this can be happen after this synchronization conditions are met: 

* ##### The message queue is empty.

* ##### There are no instances of AsyncTask currently executing a task.

* ##### All developer-defined idling resources are idle.

### 2. Packages

#### Here is some of packages we will use it in espresso and  we should know them.

    "
    espresso-core - Contains core and basic View matchers, actions, and assertions. See Basics and Recipes.
    espresso-web - Contains resources for WebView support.
    espresso-idling-resource - Espresso's mechanism for synchronization with background jobs.
    espresso-contrib - External contributions that contain DatePicker, RecyclerView and Drawer actions, accessibility checks, and CountingIdlingResource.
    espresso-intents - Extension to validate and stub intents for hermetic testing.
    espresso-remote - Location of Espresso's multi-process functionality.
    "

# B) Espresso Test Recorder

### In this part we will learn how to create UI tests with Espresso Test Recorder

### There is two primary components  that espresso tests consist which is UI interactions and assertions on View elements.

* ## Record UI interactions

### To use espresso Test Recorder there is some steps we need to follow :

#### 1. run the  Record Espresso Test

#### 2. we need to choose the device that we will recored the test from it from the Select Deployment Target window.

#### 3. we need to run our app and start adding the view that we need to test in the Record Your Test window .

* ## Add assertions to verify UI elements

### There is three main type of  assertions

* #### text is: Checks the text content of the selected View element

* #### exists: Checks that the View element is present in the current View hierarchy visible on the screen

* #### does not exist: Checks that the View element is not present in the current View hierarchy.

