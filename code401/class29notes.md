# Advanced State with Reducers

## Extracting State Logic into a Reducer

### What is the motivation for adding a reducer?

Reducers provide a predictable way to handle state updates in complex state logic. They offer a centralized place to manage state transitions, making state changes more organized and maintainable.

### What are actions in the context of a reducer? How are they different than setting state directly?

Actions in the context of a reducer are objects that describe what type of state change or side-effect you want to enact. Typically, an action has a `type` property (and optionally additional data). Instead of directly modifying state like `setState`, actions signal the intent to make a state change, and the reducer determines how the state should change in response to that action.

### What common list operation is useReduce named for, and why?

The hook is named `useReducer` (not `useReduce`). It's inspired by the "reduce" function found in many programming languages, which processes a list of values to produce a single cumulative result. In the context of `useReducer`, the idea is to "reduce" a series of actions into a new state.

### When should you switch from useState to useReducer?

You should consider switching from `useState` to `useReducer` when the state logic becomes more complex, when there are interdependencies between state values, or when you have to manage the state of multiple actions and transitions in a more predictable manner. It's especially useful for state management in larger components or when multiple state transitions should be done in a sequence.
