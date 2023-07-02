# Reading notes class 39

## [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

**What concerns are addressed by Redux Toolkit?**

- It has an immer library internally, which allows you to write simpler mutable code when updating state. You can directly modify state properties without explicitly creating copies of objects or arrays.
- It reduces the amount of boilerplate code required to set up a Redux store, define reducers, and create actions. It provides a simplified syntax and utility functions that streamline the Redux development process.
- It encourages a specific structure for defining actions and reducers. It promotes the use of "slices," which are modular units of state, actions, and reducers. This organization improves code organization and readability.

**What does configureStore() do?**

Simply put, the function simplifies the process of setting up a Redux store, like setting up sensible defaults for the store configuration. It also automatically sets up the Redux store with the specified reducers. You can pass an object that contains reducers to the reducer option of configureStore(), and it will automatically combine and configure them

**How would I use createSlice()?**

First, you would want to import the dependency, then define an initial state for the slice. Use createSlice() to create a slice of the Redux store. Pass an object with the name and initialState properties, and define the reducers object with the various actions and their corresponding reducer functions. You can then access the generated action creators and reducer by destructuring them from the slice object. Don't forget to export the action creators and reducer.

By doing so, you can define a slice of the Redux store with initial state, actions, and reducers in a concise and efficient way.

## [MobX](https://mobx.js.org/getting-started.html)

**What is Mobx?**

Mobx is a state management library for JavaScript and TypeScript applications. It provides a simple and reactive way to manage the state of your application, making it easier to track changes and update your user interface accordingly

**How does MobX make it “impossible” to produce an inconsistent state?**

It enforces strict rules and provides a reactive programming model. The state is managed through observables, which are values that can be observed for changes. When any observable value is modified, Mobx ensures that all the observers of that value are automatically notified and updated. Though it helps prevent inconsistencies, it doesn't completely eliminate the possibility!

**How would we build a reactive user interface?**

## [Tutorial](https://redux-toolkit.js.org/tutorials/overview)

**What take-away(s) did this tutorial provide?**

Overall, I learned how Redux Toolkit can streamline and enhance the development process with Redux by providing convenient abstractions, minimizing repetitiveness with code, simplifying async operations, and improving the debugging process.

## Bookmark and Review

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

[HookState](https://hookstate.js.org/)

## Reflection

**What are your learning goals after reading and reviewing the class README?**

To build out a complete React/Redux Application and understand what's going on
