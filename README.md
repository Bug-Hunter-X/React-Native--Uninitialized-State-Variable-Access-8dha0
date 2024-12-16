# React Native: Uninitialized State Variable Access

This repository demonstrates a common error in React Native: attempting to access a state variable before it has been initialized. This often results in an undefined value error.  The solution showcases the proper way to handle state updates and prevent this issue. 

## Bug Description
The `bug.js` file contains code that incorrectly accesses a state variable (`count`) before it has been assigned an initial value. 

## Solution
The `bugSolution.js` file demonstrates the corrected approach using conditional rendering or a default value to handle the scenario where the state is not yet defined.