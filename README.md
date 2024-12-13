# React useEffect Cleanup Function Issue

This repository demonstrates a bug where the cleanup function in `useEffect` is not called when the component unmounts in React 18+.  The issue seems to be related to how the component unmounts in certain scenarios. This could lead to memory leaks or unexpected behavior.

## Reproduction

1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the console logs. The cleanup function should be logged when you unmount the component.