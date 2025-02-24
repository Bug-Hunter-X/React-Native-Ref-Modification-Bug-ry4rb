# React Native Ref Modification Bug

This example demonstrates the issue of directly modifying a component's state or props through a ref in React Native.  It also shows the correct approach using the component's lifecycle methods and state management.

## Bug
The `bug.js` file illustrates the incorrect method of manipulating component state using refs.  This can lead to inconsistent UI updates and unexpected behavior.

## Solution
The `bugSolution.js` file shows the correct method, which utilizes the component's `setState` method and appropriate prop management for controlled components.

## How to reproduce the bug
1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npx react-native run-android` (or `npx react-native run-ios`).
4. Observe the unexpected behavior in the application.