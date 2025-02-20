# React useEffect Cleanup and Dependency Array Issue

This repository demonstrates a common issue encountered when using the `useEffect` hook in React: improper use of the dependency array, leading to unexpected behavior, such as infinite loops or the cleanup function not being called as expected. 

The `bug.js` file contains code exhibiting the problem, where the dependency array is missing or incorrect, resulting in the cleanup function not always being called. The `bugSolution.js` file presents the corrected code with a proper dependency array. This example shows the importance of carefully specifying dependencies for React's useEffect hook.  Understanding how useEffect's dependency array works is crucial for building predictable and performant React applications. 