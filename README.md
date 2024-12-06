# Incorrect Usage of useState Hook in React 18
This repository demonstrates a common mistake when using the `useState` hook in React 18 and how to correctly solve it.

## The Bug
The `bug.js` file contains a functional component that incorrectly updates state by directly modifying the state variable.  This is a frequent error which leads to unexpected behavior and React not re-rendering the component.

## The Solution
The `bugSolution.js` file shows the corrected implementation. It utilizes the setter function returned by `useState` to update the state, ensuring React's reactivity system works correctly.