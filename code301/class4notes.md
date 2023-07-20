# React Docs - Forms

## What is a ‘Controlled Component’?

A "Controlled Component" in React is a form element whose value is controlled by React's state. This means that the value of the form element is set and updated by React, and any changes made by the user are managed by React as well. It allows for better control and validation of form inputs.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why

Updating the state with the user's responses as soon as they enter them is generally better. It provides immediate feedback to users, enables real-time form validation, improves usability, and simplifies data management. It enhances the user experience and helps prevent errors in the form.

## How do we target what the user is entering if we have an event handler on an input field?

When the user types something in an input field, an event called `onChange` is triggered. In the event handler function we can access what the user typed using `event.target.value`. This gives us the current text entered by the user, which we can then use for various purposes, like updating the state or performing validation.

## The Conditional (Ternary) Operator Explained

## Why would we use a ternary operator?

We use a ternary operator as a shorter way to write simple conditional expressions in JavaScript. It helps make code concise and easier to read, especially when we want to assign values or execute code based on a condition.

## Rewrite the following statement using a ternary statement

``` javascript
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

rewritten:

``` javascript
console.log(x === y ? true : false);
```
