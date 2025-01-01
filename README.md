# React Memory Leak in useEffect Hook

This repository demonstrates a common memory leak in React applications caused by the improper use of the `useEffect` hook.  The `bug.js` file shows a component with a memory leak because a `setTimeout` is not properly cleaned up when the component unmounts.  The `bugSolution.js` file provides a corrected version with the cleanup function included, preventing the memory leak.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` to see the problematic code.
3. Open `bugSolution.js` to see the corrected code.