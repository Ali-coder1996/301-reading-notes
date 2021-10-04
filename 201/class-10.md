# Error Handling & Debugging

- JavaScript can be hard to learn and everyone makes
  mistakes when writing it. This chapter will help you learn
  how to find the errors in your code. It will also teach you how
  to write scripts that deal with potential errors gracefully.

> ORDER OF EXECUTION

- To find the source of an error, it helps to know how scripts are processed.
  The order in which statements are executed can be complex; some tasks
  cannot complete until another statement or function has been run:

> EXECUTION CONTEXTS

- The JavaScript interpreter uses the concept of execution contexts.
  There is one global execution context; plus, each function creates a new
  new execution context. They correspond to variable scope.

> UNDERSTANDING ERRORS

- If a JavaScript statement generates an error, then it throws an exception.
  At that point, the interpreter stops and looks for exception-handling code.

> ERROR OBJECTS

- Error objects can help you find where your mistakes are
  and browsers have tools to help you read them.

> ERROR OBJECTS CONTINUED

- Syntax Error

  1- SYNTAX IS NOT CORRECT

  2- MISSING CLOSING BRACKET

  3- MISSING COMMA IN ARRAY

  4- MALFORMED PROPERTY NAME

  5- VARIABLE DOES NOT EXIST

  6- NAMED FUNCTION IS UNDEFINED

- Type Error

  1- INCORRECT CASE FOR document OBJECT

  2- INCORRECT CASE FOR write() METHOD

  3- METHOD DOES NOT EXIST

  4- DOM NODE DOES NOT EXIST

> HOW TO DEAL WITH ERRORS

- Now that you know what an error is and how the browser treats them,
  there are two things you can do with the errors.

1- DEBUG THE SCRIPT TO FIX ERRORS

- If you come across an error while writing a script
  (or when someone reports a bug), you will need to
  debug the code, track down the source of the error,
  and fix it.
  You will find that the developer tools available in
  every major modern browser will help you with
  this task. In this chapter, you will learn about the
  developer tools in Chrome and Firefox. (The tools in
  Chrome are identical to those in Opera.)

2- HANDLE ERRORS GRACEFULLY

- You can handle errors gracefully using try, catch,
  throw, and finaily statement,
  Sometimes, an error may occur in the script for a
  reason beyond your control. For example, you might
  request data from a third party, and their server
  may not respond. In such cases, it is particularly
  important to write error-handling code.

> HOW TO LOOK AT ERRORS IN CHROME

![chrom error](https://developer-chrome-com.imgix.net/image/admin/lMl9U6EJBQDLBVYKbxX9.png?auto=format)

> HOW TO LOOK AT ERRORS IN FIREFOX

![firefox error](https://i2.wp.com/wordpress.org/support/files/2020/07/firefox-webconsole.png?resize=1024%2C607&ssl=1)

>summary

- If you understand execution contexts (which have two
  stages) and stacks, you are more likely to find the error
  in your code.

- Debugging is the process of finding errors. It involves a
process of deduction.

- The console helps narrow down the area in which the
error is located, so you can try to find the exact error.

- JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.

- If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.
