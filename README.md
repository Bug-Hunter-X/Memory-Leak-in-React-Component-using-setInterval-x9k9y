# React SetInterval Memory Leak

This example demonstrates a common error in React components: using `setInterval` within `useEffect` without providing a cleanup function. This can lead to memory leaks and unexpected behavior, such as a counter continuing to increment even after the component unmounts. 

The `bug.js` file shows the problematic code, while `bugSolution.js` demonstrates the correct way to handle `setInterval` within a React component to prevent memory leaks.