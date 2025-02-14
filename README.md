# React Router v6 Catch-all Route Issue

This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router v6.  The problem arises when the catch-all route unintentionally intercepts other routes, leading to unexpected behavior.

## Problem
The provided `App.js` file showcases how the `/*` route (designed to handle 404 errors) is incorrectly capturing all other routes, including `/about`.

## Solution
The solution, `AppSolution.js`, demonstrates the correct way to structure routes to avoid this issue. The order of routes matters; more specific routes should be defined before catch-all routes.
