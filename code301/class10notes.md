# Understanding the JavaScript Call Stack

## What is a ‘call’?

In programming, a 'call' refers to the act of invoking or executing a function or method. When you 'call' a function, you're telling the computer to run the code inside that function and perform the actions it defines.

## How many ‘calls’ can happen at once?

Think of 'calls' like people talking to the computer. How many people can talk at the same time depends on how good the computer is at multitasking. If it's powerful, it can handle many calls at once. But if it's not, it might need to finish one call before starting another.

## What does LIFO mean?

At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call). When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack

```javascript
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction(); 
```

1. When secondFunction() gets executed, an empty stack frame is created. It is the main (anonymous) entry point of the program.
2. secondFunction() then calls firstFunction()which is pushed into the stack.
3. firstFunction() returns and prints “Hello from firstFunction” to the console.
4. firstFunction() is pop off the stack.
5. The execution order then move to secondFunction().
6. secondFunction() returns and print “The end from secondFunction” to the console.
7. secondFunction() is pop off the stack, clearing the memory.

## What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## JavaScript error messages

## What is a ‘reference error’?

A 'Reference Error' is a type of error that occurs in programming when you try to use a variable or function that hasn't been declared or defined. In simpler terms, it's like asking for something that doesn't exist.

## What is a ‘syntax error’?

I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

## What is a ‘range error’?

A 'Range Error' is a type of error that occurs in programming when you try to use a value that is outside the acceptable range or bounds. It's like trying to pick a number that's not on the menu.

## What is a ‘type error’?

A 'Type Error' is a type of error that occurs in programming when you try to perform an operation on a value of a type that is not supported by that operation. It's like trying to use a tool in a way it wasn't designed for.

## What is a breakpoint?

A 'breakpoint' in programming refers to a specific point in your code where you instruct the debugger to pause the execution of the program. This pause allows you to inspect the program's state, variables, and data at that particular moment.

## What does the word ‘debugger’ do in your code?

A 'debugger' is a tool in programming that helps you find and fix errors in your code. It allows you to control the execution of your program, inspect variables, and analyze the flow of your code step by step. When you're debugging, you're essentially investigating and solving issues in your code.
