# Day(3)

# Maps, primitives, File I/O

## Primitives V.S Objects:
* ## Java Type System.
### We hava two fild type system in java consisting of primitives such as int, boolean and reference types such as Integer, Boolean.

### Also we can do a conversion between the primitive and reference types, we have to type of conversion :
1. #### Autoboxing : converting a primitive type to a reference one.
2. #### Unboxing : converting a reference type to a primitive one.

* ## Pros and Cons.

### Defferint in the size for the primitive and  reference type.
### in the primitive :
* #### boolean – 1 bit
* #### byte – 8 bits
* #### short, char – 16 bits
* #### int, float – 32 bits
* #### long, double – 64 bits

### in the reference :

* #### Boolean – 128 bits
* #### Byte – 128 bits
* #### Short, Character – 128 bits
* #### Integer, Float – 128 bits
* #### Long, Double – 192 bits

# Exceptions in Java.

### What Is an Exception?
####  exception is an event, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions.

### What is happen when an error occurs within a method?
#### The method will creates an object and hands it off to the runtime system. The object, called an exception object, contains information about the error, including its type and the state of the program when the error occurred. Creating an exception object and handing it to the runtime system is called throwing an exception.

## The Catch or Specify Requirement
### In this part it's telling what happen when the code throw a certain exceptions. 
### the first thing we can do by a try statement that catches the exception. The try must provide a handler for the exception,or  a method that specifies that it can throw the exception. The method must provide a throws clause that lists the exception.
## Catching and Handling Exceptions.

### In this section I learned how how to use the exception handler components.
# Scanning
### A Scanner breaks its input into tokens using a delimiter pattern, which by default matches whitespace. The resulting tokens may then be converted into values of different types using the various next methods.