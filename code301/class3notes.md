# React Docs - lists and keys

## What does .map() return?

When you call the .map() method on an array, it iterates over each element of the array and applies a callback function to each element. It then returns a new array containing the results of applying the callback function to each element.

## If I want to loop through an array and display each value in JSX, how do I do that in React?

To loop through an array and display each value in JSX in a React component, you can use the .map() method inside your component's rendering function.

## Each list item needs a unique ____

Each list item needs a unique `key`.

## What is the purpose of a key?

The purpose of a key in React is to help the framework keep track of individual elements in a list. When you render a list of elements, React needs to know which element is which, especially when the list changes.

## The Spread Operator

## What is the spread operator?

In JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

## List 4 things that the spread operator can do

1. Copying Arrays
2. Merging Arrays
3. Copying Objects
4. Merging Objects

## Give an example of using the spread operator to combine two arrays

An example of this can be seen when I use the spread operator (...) to combine `array1` and `array2` into a new array called `array2`. The resulting array, `combinedArray`, contains all the elements from `array1` followed by all the elements from `array2`.

## Give an example of using the spread operator to add a new item to an array

An example of this can be seen when we have an originalArray with elements `[1, 2, 3]`. We want to add a new item `4` to the array without modifying the `originalArray`. To do this, we use the spread operator (...) to create a new array `newArrayWithNewItem`. The spread operator takes all the elements from the `originalArray` and then adds the new item `4` at the end of the array, resulting in `[1, 2, 3, 4]`.

## Give an example of using the spread operator to combine two objects into one

An example of this can be seen when we have two objects `person` and `address`. By using the spread operator (...), we combine the properties from both objects into a new object called `personWithAddress`. The spread operator takes all the properties from `person` and `address` and creates a new object with all the properties merged together.

## How to Pass Functions Between Components

## In the video, what is the first step that the developer does to pass functions between components?

The first step is to define the function in the parent component and then pass it down to the child component as a prop. This allows the child component to access and execute the function when needed.

## In your own words, what does the increment function do?

The increment function iterates through the `people` array, and if it finds a name that matches the one passed in as an argument, it increments the count of occurrences for that name within the `people` array by one.

## How can you pass a method from a parent component into a child component?

In React, you can pass a method from a parent component to a child component by including the method as a prop when rendering the child component in the parent component's JSX. The child component can then access and use the method through its props and call it when needed, such as when an event occurs. This allows parent components to share functionality with their child components.

## How does the child component invoke a method that was passed to it from a parent component?

In a child component, you can invoke a method that was passed to it from a parent component by calling the method through its props. When a method is passed from the parent component as a prop to the child component, it becomes accessible within the child component's `props` object.
