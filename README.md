# Unnecessary Re-renders in React useEffect Hook

This example demonstrates a common React issue: an `useEffect` hook that triggers an infinite render loop due to the absence of dependencies.  The console log shows how the component renders repeatedly.  The solution demonstrates how to properly use the dependency array to control when the effect runs.
