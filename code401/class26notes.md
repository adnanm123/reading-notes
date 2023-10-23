# Reading: Component Based UI

## React Quick Start

### What are the building blocks of a React app?

The primary building blocks of a React application are "components." These are reusable pieces of code that manage their own content, presentation, and behavior.

### What is the difference between an HTML element and a React component?

An HTML element is a standard component of the HTML language, defining parts of a webpage. A React component, however, can represent both HTML elements and other user-defined components, encapsulating more complex structures and behaviors in reusable packages.

### What is JSX and why do we use it?

JSX is a syntax extension for JavaScript, recommended for use with React. It looks like HTML and enables developers to write HTML-like code for elements and components in a React application, which makes the structure of the rendering more readable and understandable. We use it because it simplifies the creation of React trees of components with a syntax familiar to many developers.

### Describe the process of embedding JavaScript expressions in JSX.

JavaScript expressions can be embedded in JSX by wrapping the expression in curly braces `{}`. For example: `<div>{1 + 1}</div>` would render `<div>2</div>`.

### Does React or JSX have any special features for iteration or conditional logic?

Yes, JSX allows JavaScript expressions to be embedded, so you can use JavaScript's conditional logic (like if statements, ternary expressions, and logical operators) and iteration methods (like `map()`, `forEach()`, etc.) within JSX.

### How does React know to respond to a user’s inputs?

React knows to respond to user inputs through "event handling." Functions can be passed as props to components and executed in response to events (like onClick, onChange, etc.), allowing React to respond to user actions.

### What word indicates that a React component manages data with a Hook?

The word "use" at the beginning of a function name indicates that a React component manages data with a Hook (e.g., `useState`, `useEffect`, `useContext`, etc.).

### How can two react components share data?

Two React components can share data through "props", lifting state up to a common ancestor component, or using React context. "Props" are used to pass data from parent to child component, whereas context is used to pass data through the component tree without having to pass props down manually at every level.

## Render and Commit

### What are the three steps of refreshing a React UI?

* **Step 1: State/Props Change:** The process begins when there is a change in a component's state or props.
* **Step 2: Re-render:** React responds to the changes by re-rendering the relevant components.
* **Step 3: DOM Update:** React updates the DOM to reflect the new component output, specifically in the parts that changed.

### How do you trigger updates to a component after the initial render?

You trigger updates to a component after the initial render by changing its state using the `setState()` function (in class components) or the state-setting function from `useState()` (in functional components). Changes in props received from parent components can also trigger an update.

### Does React recreate DOM nodes on every rerender?

No, React does not recreate DOM nodes on every rerender. It uses a virtual DOM to perform a diffing process, comparing new render output with the previous one. Only the nodes that have changed are updated in the actual DOM.

### After React has updated the DOM, what still needs to happen before the user sees the change?

After React has updated the DOM, the browser needs to repaint the UI. This process involves the browser's rendering engine taking the updated DOM and re-rendering the pixel data on the screen, a step called "reflow" or "layout," followed by "painting." This is handled by the browser itself and is not part of React's processes.
