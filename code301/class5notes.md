# React Docs - Thinking in React

## What is the `single responsibility principle` and how does it apply to components?

The `single responsibility principle` in software development means that each component should have one clear purpose or task. Applied to components, it means each component should focus on a specific functionality or part of the user interface. This approach improves maintainability, readability, and reusability in the code. By keeping components small and focused, it becomes easier to understand and manage them, leading to a more organized and efficient application.

## What does it mean to build a ‘static’ version of your application?

Building a "static" version of your application means creating the visual appearance and layout of the user interface without adding any interactive or dynamic features.

## Once you have a static application, what do you need to add?

Once you have a static application, you need to add `state` which will enable interactivity for user actions, dynamic content that can change based on user input or real-time data, user input handling for validation, navigation between different views or pages, and error handling for a smoother user experience.

## What are the three questions you can ask to determine if something is state?

1. Does it change over time?
2. Can it be passed as a prop from a parent component?
3. Does it affect multiple components in the application?

## How can you identify where state needs to live?

To identify where state needs to live in a React application, you look for the data that changes over time, find the components that depend on or use that data, and then move the state up to a common parent component encompassing those components while passing the state down as props for access and updates.

## Higher-Order Functions

## What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them, are called "higher-order functions".

## Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?

Line 2 of the `greaterThan` function returns another function, which evaluates whether the value of m is greater than n, resulting in a true value.

## Explain how either map or reduce operates, with regards to higher-order functions

`map`:
`map` takes an array and a callback function as input.
It applies the callback function to each element of the array. The result is a new array with transformed values based on the callback function.

`reduce`:
`reduce` takes an array, a callback function, and an initial value as input.
It applies the callback function to each element of the array, updating an accumulator. The final result is the accumulated value after processing all elements.
