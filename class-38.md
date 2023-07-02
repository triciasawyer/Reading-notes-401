# Reading notes class 38

## [async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)

**Why use Redux middleware?**

1. Middleware allows you to handle side effects, such as making API calls, accessing the browser's local storage, or logging. By intercepting actions, middleware can perform these side effects and then dispatch new actions to update the Redux state accordingly.
2. Middleware simplifies handling asynchronous operations in Redux. It enables you to dispatch actions with asynchronous logic, such as API requests, and handles the process of dispatching multiple actions based on the asynchronous results.

**Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.**

- A component triggers an action to perform an asynchronous operation, like fetching data from an API.
- Middleware intercepts this action and can do additional tasks like making API calls or modifying the action.
- Once the asynchronous operation is complete, the middleware dispatches a success or failure action.
- The reducer receives the success or failure action and updates the state with the fetched data or error information.
- Connected components that are subscribed to relevant parts of the state can access the updated data and show it in the user interface.
- If there's an error, components can handle it by displaying error messages or taking appropriate actions based on the error information.

To summarize thsis, the flow involves triggering an action, middleware handling the asynchronous operation, updating the state based on success or failure, and components using the updated data or handling errors. It helps manage asynchronous operations in a predictable and organized way.

**How are we accommodating async in our Redux app?**

Redux Thunk middleware

## [thunk middleware](https://github.com/reduxjs/redux-thunk)

**Why would you need redux-thunk middleware?**

To handle asynchronous operations and enable the dispatching of functions as actions.

Redux Thunk allows you to dispatch actions that represent asynchronous operations, such as making API requests or interacting with a backend server. Without Redux Thunk, Redux only supports dispatching plain objects as actions synchronously.

Also, when fetching data from an API, Redux Thunk helps you manage the asynchronous nature of the operation. It allows you to dispatch loading actions, perform the API request, and dispatch success or error actions based on the API response. This ensures a smoother data flow and better user experience.

**Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.**

Function

**Describe how any return value from the inner thunk function will be made available.**

The return value from the inner thunk function is not directly made available outside the thunk. Instead, you have control over when and how to dispatch actions. You can choose to dispatch actions synchronously within the thunk function or dispatch them based on the result of the asynchronous operation. This allows you to handle complex asynchronous flows and update the Redux store accordingly

## Reflection

**What are your learning goals after reading and reviewing the class README?**

Take in as muhc as I can about Thunk Middleware and how that works along with redux actions
