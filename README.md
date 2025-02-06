# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The `useEffect` hook, when used without a dependency array, runs after every render. This can lead to an infinite loop if the effect itself causes a re-render. 

The `bug.js` file showcases the problematic code. The solution is provided in `bugSolution.js`. This example highlights the importance of specifying dependencies in the `useEffect` hook to prevent unintended side effects.