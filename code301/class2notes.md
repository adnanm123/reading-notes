# React lifecycle

## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Based off the typical lifecycle of a React component, the 'render' method is executed first before the 'componentDidMount' method.

## What is the very first thing to happen in the lifecycle of React?

The constructor for a React component is called before it is mounted.If the component is a subclass you should call super(props), or the props will be undefined. constructors can be used to assign state using this.state or to bind event handle methods to an instance.

## Put the following things in the order that they happen

1. constructor
2. render
3. componentDidMount
4. React Updates
5. componentWillUnmount

## What does componentDidMount do?

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.

## React State Vs Props

## What types of things can you pass in the props?

 In React, you can pass various types of data as props to a component, such as strings, numbers, objects (like arrays or custom objects), functions, React elements, JSX elements, callbacks, and event handlers.

## What is the big difference between props and state?

Props are used to pass data from parent to child components, while state is used to manage and handle data within a component itself. Props are read-only and cannot be changed directly, while state can be updated using setState() to re-render the component when changed.

## When do we re-render our application?

We re-render our application in React whenever there is a change in the component's state or when it receives new props from its parent component.

## What are some examples of things that we could store in state?

Some examples of things that we could store in state in a React component are user input data, component-specific data like counters or toggles, API responses, error messages, loading indicators, authentication status, filtered data, and display modes.
