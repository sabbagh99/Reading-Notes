# Day(10)
### So today i think we will learn something important its the Debugging, First let me summary the chaptor(10) from Duckett JavaScript Book.

* Chaprar(10) ERROR HANDLING & DEBUGGING.

> JavaScript its hard to learn and evrey one who writing a code can make mistake so this chapter will help us to find our error.

1. EXECUTION CONTEXT & HOISTING : In first place what happen when we enter an execution context when we do this tow things happen :

A) Prepare :

>The new scope is created then  Variables, functions, and arguments are created and in the end The value of the this keyword is determined.

B) Execute :
> Now it can assign values to variables and reference functions and run their code in the end execute statements.

2. Error object : when error object created in console it must contain the following proparty name (type of extintion), massage (discrebtion), file number name of javaScript file , line number (line number of error).

3. And to know what error we have so there are to many type of error this type is :

A) Error: Generic error - the other errors are all based upon this error.

B) Syntax Error: Syntax has not been followed.

C) Ref erenceError: Tried to reference a variable that is not declared/within scope.

D) TypeError: An unexpected data type that cannot be coerced

E) Range Error: Numbers not in acceptable range.

F) URI Error: encodeURI ().decodeURI(),and similar methods used incorrectly .

G) Eval Error: eval() function used incorrectly.

4. When you see one of the error massage how you can handle with them.

A) DEBUG THE SCRIPT TO FIX ERRORS : you can do this by using devoloper option and consle in the browser.

5. You can use from inspect in your browser  the source for your JavaScript file and using breakpoint you can pause the execution then check the values stored in variables at that point in time.
