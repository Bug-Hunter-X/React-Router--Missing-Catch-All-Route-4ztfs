# React Router: Missing Catch-All Route

This repository demonstrates a common error in React Router v6:  not including a catch-all route to handle unexpected or invalid URLs.

## Problem
The `App.js` component uses `react-router-dom` to define routes.  However, it lacks a route to handle paths that don't match `/` or `/about`. This results in the application not displaying anything or potentially causing unexpected behavior.

## Solution
The `AppSolution.js` component demonstrates the correct approach: adding a `Route` with `path="*"` to handle any URL that doesn't match the previously defined routes. This ensures a more robust and user-friendly experience.