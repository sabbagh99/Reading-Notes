# A) Intents, Activities, and SharedPreferences

## 1. Tasks : " task is a collection of activities that users interact with when performing a certain job "

## 2. Back Stack : if you are in activity and you start another one the new activity is pushed on the top of the stack and takes focus. The previous activity remains in the stack, but is stopped.

## Managing Tasks : android managing his tasks by placing all activeties in  the same task and in a "last in, first out" stack 

# B) Save key-value data

## SharedPreferences : we can use it if we  have a relatively small collection of key-values that you'd like to save,

### Get a handle to shared preferences

#### to do that we need to  create a new shared preference file or access an existing one by calling one of these methods:

* #### getSharedPreferences() : Use this if you need multiple shared preference files identified by name

* #### getPreferences() — Use this from an Activity if you need to use only one shared preference file for the activity.


#### If we want to write  a shared preferences file,  we need to create a SharedPreferences.Editor by calling edit() on your SharedPreferences.

#### Read from shared preferences to retrieve values from a shared preferences file, call methods such as `getInt()` and `getString()`, providing the key for the value you want, and optionally a default value to return if the key isn't present.