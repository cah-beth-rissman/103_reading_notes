# Class 08 Notes

## Focus on Expressions and Operators

### [Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

+ Comparison operators
+ Assignment operators

### [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

> Loops offer a quick and easy way to do something repeatedly
+ A **for loop** repeats until a specified condition evaluates to false. 

+ When a for loop executes, the following occurs:

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
If present, the update expression incrementExpression is executed.
Control returns to Step 2.

+ A **while** statement executes its statements as long as a specified condition evaluates to 'true'
+ If the condition becomes 'false', statement within the loop stops executing and control passes to the statement following the loop.
+ The condition test occurs before statement in the loop is executed. If the condition returns 'true', statement is executed and the condition is tested again. If the condition returns 'false', execution stops, and control is passed to the statement following 'while'.