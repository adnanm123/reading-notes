# Reading: `useState()` Hook

## Thinking in React

### Summarize the five steps of thinking in react.

1. **Break The UI Into A Component Hierarchy:** Analyze the mockup and break down your UI into individual components represented as a hierarchy. Components should ideally represent one piece of your data model.

2. **Build A Static Version in React**: Create a version that takes your data model and renders the UI but has no interactivity. This lets you build and understand the component hierarchy without needing to worry about state changes or interactivity.

3. **Identify The Minimal (but complete) Representation Of UI State:** Determine the absolute minimal representation of the state your application needs. This means understanding what data needs to be mutable and what can remain immutable, ensuring you don't replicate data from props in the state.

4. **Identify Where Your State Should Live:** Identify which component in your hierarchy should own the state. The state should live in the parent component or be lifted up to the closest common ancestor of all components that need it if more than one component needs access to the state.

5. **Add Inverse Data Flow:** Build in the ability for child components to update the state of parent components. Essentially, this involves creating functions in the parent components that can update the state and passing those functions down to the children through props so that when the child component triggers an event, it calls the passed-down function and updates the parent component's state.

## State: A Component’s Memory

### What is one reason a local variable isn’t sufficient for managing a React component?

* _Reason:_ Local variables don't trigger a re-render when they change. In React, a component's state is what allows it to maintain dynamic information and re-render when that information changes. Local variables don't have this capability, meaning the UI wouldn't update in response to changes in those variables.

### What is the argument to the useState hook, and what are the two parts of its return array?

* _Argument:_ The `useState` hook takes one argument, which is the initial state value.
* _Two Parts of Return Array:_

    2.1. _State Variable:_ The first item in the return array is the state variable itself, which holds the current state value.
    2.2. _Setter Function:_ The second item is a function that allows you to update the state variable, triggering a re-render with the new state value.

### How can Component A access state from Component B?

3.1. _Lifting State Up:_ If Components A and B have the same parent component, the state can be lifted to the parent, and functions can be passed as props to update and access the state.
3.2. _Context:_  React's Context API allows you to create global state that can be accessed by any component within the same context tree.
3.3. _State Management Libraries:_ Libraries like Redux or MobX manage the state outside of the component hierarchy and provide mechanisms to read and update the state from any component.
