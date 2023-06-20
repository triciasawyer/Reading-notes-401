# Reading notes class 29

## [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

**What is the motivation for adding a reducer?**
The useReducer hook is helpful when handling complex state management in a more predictable and centralized manner. While useState is suitable for managing simple state updates, it can become cumbersome when dealing with state that depends on the previous state or when multiple state transitions need to be coordinated. By using a reducer function with useReducer, you can define a clear and concise set of actions that describe how the state should be updated. The reducer function takes the current state and an action as input and returns the new state based on the action type. This promotes a more declarative and predictable approach to state updates.

**What are actions in the context of a reducer? How are they different than setting state directly?**
Actions in the context of a reducer serve as explicit instructions for the reducer function to determine how the state should be updated. They provide structure, centralization, and flexibility in managing state transitions, which differs from directly setting state and allows for more predictable and maintainable state management.

**What common list operation is useReduce named for, and why?**
The common list operation called “reduce” or “fold.” The purpose of the reduce operation is to iteratively combine the elements of a list into a single value. The reduce operation is well-known and widely used in functional programming and various programming languages. By naming the hook useReducer, React leverages the familiarity with this common list operation, making it intuitive for developers to understand the purpose and functionality of the hook.

**When should you switch from useState to useReducer?**
Deciding to switch from useState to useReducer should be based on the specific needs of your application. If your state management is simple and straightforward, useState can still be the preferred choice. useReducer is best suited for more complex state management scenarios. So, if your component’s state management involves complex logic, such as multiple state transitions that depend on each other or intricate conditional updates, using useReducer can make your code more organized and maintainable. The reducer function allows you to centralize and encapsulate the state update logic, making it easier to reason about and modify.

## Bookmark and Review

[useReducer hook](https://react.dev/reference/react/useReducer)

[Keeping Components Pure](https://react.dev/learn/keeping-components-pure)

[Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)

## Reflection

**What are your learning goals after reading and reviewing the class README?**
Learning about actions and being able to use, useReduce efficiently.

## Things I want to know more about
