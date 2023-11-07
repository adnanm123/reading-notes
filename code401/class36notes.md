# Reading: Application State with Redux

## Dan Abramov Redux Tutorials

### What is the first principle of Redux?

The first principle of Redux is that all application state is contained within a single store. It emphasizes that there's a single source of truth for the entire state of your application, which makes it easier to track changes and manage the state.

### what is a store and what do we use our reducers for within that store?

* **Store:** A store is an object that holds the entire state of a Redux application. Think of it as a container that holds all the information that your application needs to run.
* **Reducers:** Reducers are functions that determine how the state should change in response to actions sent to the store. They take the previous state and an action as arguments and return a new state. In essence, they manage updates to the state by returning a new state object based on the action received.

### Name three Redux store methods given to us by createStore and describe their use.

* `getState()`: This method is used to retrieve the current state object of the application from the store.
* `dispatch(action)`: It is used to send an action to the store. Actions are payloads of information that send data from the application to the store and trigger state changes through reducers.
* `subscribe(listener)`: This method allows you to register a listener that will be called every time an action has been dispatched, and the state tree might have changed. It's like setting up an alert system that notifies you when something changes.

### Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.

Imagine you have a team working on different parts of a project, and each team member is responsible for one part. At the end of the day, you need to combine everyone's work into a complete project report. That's what `combineReducers()` does for Redux.

In Redux, the state of the app is divided into different sections, and each section can have its own manager, which is a reducer. `combineReducers()` is a helper function that takes all the different reducers and combines them into one big reducer. This big reducer then manages the entire state of the app. It's useful because it helps keep the code for managing different parts of the state organized and easy to manage. It allows different teams or individuals to work on different parts of the state independently without stepping on each other's toes.
