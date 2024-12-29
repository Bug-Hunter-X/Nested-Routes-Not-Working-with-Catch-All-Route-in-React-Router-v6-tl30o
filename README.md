# React Router v6 Nested Routes Issue

This repository demonstrates a common issue encountered when using nested routes with a catch-all route (`/*`) in React Router v6.  The catch-all route unintentionally intercepts all requests, preventing other routes from rendering correctly.

The `bug.js` file shows the problematic code.  The solution, found in `bugSolution.js`, demonstrates how to fix this issue by using the `useLocation` hook and careful route order.