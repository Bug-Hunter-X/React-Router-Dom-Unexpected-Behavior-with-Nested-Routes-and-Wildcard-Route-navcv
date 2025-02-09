# React Router Dom Unexpected Behavior with Nested Routes and Wildcard Route

This repository demonstrates an unexpected behavior in React Router Dom v6 when using nested routes and a wildcard route ('*').  The wildcard route does not correctly catch all unmatched routes when nested routes are present. 

## Problem Description

The provided code uses nested routes. However, if you navigate to a path that doesn't match any of the defined routes, the wildcard route ('*') does not render. Instead, the application seems to render nothing, or a previous route's component.

## Solution

The solution involves restructuring the routes to prioritize the wildcard route.  A more detailed explanation is provided in the `bugSolution.js` file.