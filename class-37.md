# Reading notes class 37

## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

**Why create multiple reducers?**

- As your application grows, it becomes more complex and contains different domains or slices of state. By creating multiple reducers, you can handle each domain separately and keep the related logic and state management contained within a specific reducer.
- You can write focused unit tests

**How would you combine multiple reducers?**

By using the combineReducers function provided by the Redux library

**How will you manage state as an immutable object? why?**

Managing state as an immutable object means that the state cannot be modified directly. Instead, any changes to the state result in the creation of a new state object. With this, you benefit from it by having predictable state changes, better code performance, and time-travel debugging!

## [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)

**combineReducers is a utility function to simplify the most common use case when writing ___ _____ .**

Redux applications

**Explain how combineReducers assembles the new state tree.**

combineReducers assembles the new state tree by combining multiple reducer functions into a single reducer. It takes an object as input, where each key represents a slice of the state and the corresponding value is the reducer function responsible for managing that slice.

When an action is dispatched, the combined reducer calls each individual reducer with the current state slice and the action. Each reducer independently handles its own slice of the state and returns the updated state slice. combineReducers then combines all the updated state slices into a single state object, which becomes the new state tree.

**How would you define initial state in an app using combineReducers?**

the initial state is defined as an object where each key represents a slice of the state and the corresponding value is the initial state for that slice. The initial state object is then passed as an argument to the createStore function when setting up the Redux store

## [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

**Why will you want to split your reducing functions as your app becomes more complex?**

A few reasons why you will want to do so:

- Allows you to separate the logic for handling different parts of the state. Each reducing function becomes responsible for managing a specific slice of the state, focusing on a specific domain or feature. This separation promotes modularity and makes the codebase more organized and maintainable
- Makes it easier to debug and test your app. With smaller, focused reducers, it becomes easier to identify and fix issues within the specific parts of the state. It also allows for more targeted testing.

**The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.**

combineReducers, createStore

**What is a popular convention when naming reducers?**

Use descriptive names that indicate the slice of state they handle. The general pattern is to name the reducer based on the specific domain or feature of the state it manages

## Reflection

**What are your learning goals after reading and reviewing the class README?**

To better understand reducer and be able to walk away with the knowledge of using that function confidently
