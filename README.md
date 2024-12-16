# React 19: Unexpected State Behavior
This repository demonstrates a common error when working with React state updates, specifically the incorrect direct manipulation of state outside of the provided `setState` function in React 19.  The bug showcases asynchronous updates of state causing inconsistencies, and the solution emphasizes the importance of using the `setState` (or the functional `setCount`) method for all state changes.