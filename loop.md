# Operators and Loops

## Operators

For operators please refer [programing JS](pjs.md)

## Loops!

> [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration) offer a quick and easy way to do something repeatedly. 

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

## For Statement

A for loop repeats until a specified condition evaluates to false. 

` for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement `

When a for loop executes, the following occurs:

- The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.

- The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)

- The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.

- If present, the update expression incrementExpression is executed.
Control returns to Step 2.

## While Statement.

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

```

 while (condition)
  statement

```

If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

***

[**Home**](https://rushabhjsoni.github.io/reading-notes/)