# React Router Dom v6 Nested Routes Not Rendering

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6. The problem lies in how nested routes are defined and matched. The parent route renders, but its child routes fail to render.

## Problem Description

The `App.js` file contains a basic setup with nested routes.  The `Home`, `About` routes work, but the dynamic route `/users/:id` does not render the `User` component when navigating to a path like `/users/1`. This behavior isn't expected and indicates a potential issue in the route configuration.

## Solution

The solution involves verifying route paths and ensuring the `Routes` component is used correctly for route matching.  The solution file (`bugSolution.js`) demonstrates the corrected implementation.