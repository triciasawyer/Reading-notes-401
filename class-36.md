# Reading notes class 36

## [Dan Abramov Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)

**What is the first principle of Redux?**

Single Source of Truth. It means that the entire application state is stored in a single JavaScript object called the store. This store represents the single source of truth for the application's data. By having a centralized store, it becomes easier to manage and maintain the state of the application, making it more predictable and easier to debug

**What is a store and what do we use our reducers for within that store?**

A store is an object that holds the application state and provides methods to interact with it. It is the central piece of Redux and serves as the single source of truth for the application's state.

**Name three Redux store methods given to us by createStore and describe their use.**

- The getState() method is used to retrieve the current state stored in the Redux store. It returns the current state object, allowing you to access and read the application state
- The dispatch(action) method is used to dispatch an action to the Redux store. It is the primary way to trigger state changes in Redux. When you dispatch an action, it is passed to the reducers, which then determine how the state should be updated based on the action's type and payload
- The subscribe(listener) method allows you to register a listener function that will be invoked whenever the state in the Redux store changes. It enables you to react to state updates and perform additional logic or trigger UI updates in response to changes in the application state

**Explain to a non-technical recruiter what combineReducers() does and why it is useful.**

Say you have a large puzzle consisting of different sections. Each section represents a specific aspect of your application's state, such as user information, products, or settings. Now, instead of trying to solve the entire puzzle at once, you can break it down into smaller, more manageable sections and assign different people (reducer) to work on each section. Each person focuses on solving their assigned section of the puzzle, making it easier to handle and maintain.

## Bookmark and Review

[worlds easiest guide to redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

[testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Redux Docs](https://redux.js.org/)

## Additional Questions

**Looking ahead at this module’s course schedule, What do you look forward to learning?**

I am really looking forward to learning about Graphs and React Native! Also, the final exam prep. I am excited to put my knowledge to the test and grow from there.

**What are your learning goals after reading and reviewing the class README?**
To take on Redux and just navigate through that content.
