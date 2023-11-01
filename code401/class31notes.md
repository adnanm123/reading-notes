# Reading: Context API

## Choosing the State Structure

### Summarize the five principles for structuring state

1. **Single Source of Truth:** Store all your state data in one place, making it easier to manage and track changes.
2. **State Should Be Read-Only:** Always make copies and modify the copies rather than changing the state directly, ensuring data integrity.
3. **Changes Using Pure Functions:** Use functions that take the previous state and return a new state without side effects.
4. **State Should Be Normalized:** Avoid nested state and keep all data on a flat level with references to prevent redundancy.
5. **Keep Only Minimally Required State:** Don't store derived data; compute what's needed on-the-fly to keep state lean and efficient.

## Passing State Deeply with Context

### What problem do Contexts aim to solve?

Contexts aim to solve the problem of passing data directly through multiple component layers, eliminating "prop drilling" and making it easier to share state across different components.

### What is one technique to try before useContext?

Before using `useContext`, you can try passing props directly to child components or use component composition.

### What hook complements useContext for complex applications?

The `useReducer` hook complements `useContext` for complex applications, allowing more structured state management and handling of actions.
