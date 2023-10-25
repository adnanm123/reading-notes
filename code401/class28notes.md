# Component Lifecycle / useEffect Hook

## useEffect hook

### What is the main intended use case for the useEffect hook?

* The main use case for the `useEffect` hook is to perform side effects (like data fetching, DOM manipulation, setting up subscriptions, etc.) in functional components after they render.

### How does the effect’s logic interact with the component?

* The effect's logic runs after the component renders and can interact with the component's state, props, and other lifecycle events. It allows components to "react" to changes in a way similar to lifecycle methods in class components.

### What is the importance of the return value from the effect’s logic function?

The return value of the effect’s logic function is an optional cleanup function. This function is used to perform any necessary cleanup actions (like unsubscribing from a subscription) before the component is unmounted or before the effect runs again.
