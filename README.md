# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook that leads to an infinite rendering loop.  The bug arises from incorrectly updating state within the dependency array of `useEffect`, causing it to run continuously and never complete.  The solution shows how to correctly manage state updates within `useEffect` to prevent this type of infinite loop.

## Bug
The `bug.js` file contains the erroneous code that causes the infinite loop.

## Solution
The `bugSolution.js` file provides the corrected implementation.