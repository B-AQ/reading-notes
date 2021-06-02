
# JS book

*Chapter 10, **Error Handling & Debugging**

## Execution context & Hoisting

Each time a script enters a new execution context, there are two phases of activity:

- Prepare

1. The new scope is created
1. Variables, functions, and arguments are created
1. The value of the this keyword is determined

- EXECUTE

1. Now it can assign values to variables
1. Reference functions and run their code
1. Execute statements

---

## Scope

In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.

## Errors

 If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code.

 **Errors Errors**
 There are *seven types* of built-in error objects in JavaScript. You'll see them on the next two pages:

Object|Description|
|---|---|
|Error|Generic error - the other errors are all based upon this error|
|SyntaxError|Syntax has not been followed|
|ReferenceError|Tried to reference a variable that is not declared/within scope|
|TypeError|An unexpected data type that cannot be coerced|
|RangeError|Numbers not in acceptable range|
|URIError|encodeURI ().decodeURI(),and similar methods used incorrectly|
|EvalError|eva l () function used incorrectly|

---

### Dealing with Errors

Now that you know what an error is and how the browser treats them, there are two things you can do with the errors.

1. DEBUG THE SCRIPT TO FIX ERRORS
1. HANDLE ERRORS GRACEFULLY

---

### Chrome

How to look at Errors in **Chrome**

The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.

Typing in the console in **Chrome**

You can also just type code into the console and it will show you a result.

Writing from the *script to the console*

Browsers that have a console have a console object, which has several methods that your script can use to display data in the console. The object is documented in the Console API.

- The ``console.log()`` method can write data from a script to the console. If you open console-l og. html, you will see that a note is written to the console when the page loads.




#### Summary

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.

- Debugging is the process of finding errors. It involves a process of deduction.

- The console helps narrow down the area in which the error is located, so you can try to find the exact error.

- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.

- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.

-Use them to give your users helpful feedback.
