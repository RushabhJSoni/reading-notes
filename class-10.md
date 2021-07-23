## Error handling and Debugging.

JavaScript can be hard to learn and everyone makes 
mistakes when writing it. This chapter will help you learn 
how to find the errors in your code. It will also teach you how 
to write scripts that deal with potential errors gracefully. 


### ORDER OF EXECUTION 

To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run

### Execution contexts

The JavaScript interpreter uses the concept of execution contexts. 
There is one global execution context; plus, each function creates a new 
new execution context. They correspond to variable scope.

#### Every statement in a script lives in one of three 
execution contexts: 

- GLOBAL CONTEXT 
Code that is in the script, but not in a function. 
There is only one global context in any page. 

- FUNCTION CONTEXT 
Code that is being run within a function. 
Each function has its own function context. 

- EVAL CONTEXT (NOT SHOWN) 
Text is executed like code in an internal function 
called eva l {) (which is not covered in this book). 

- VARIABLE SCOPE 
The first two execution contexts correspond with the 
notion of scope 

- GLOBAL SCOPE 
If a variable is declared outside a function, it can 
be used anywhere because it has global scope. 
If you do not use the var keyword when creating 
a variable, it is placed in global scope. 

- FUNCTION-LEVEL SCOPE 
When a variable is declared within a function, 
it can only be used within that function. This is 
because it has function-level scope.

[**Home**](https://rushabhjsoni.github.io/reading-notes/)