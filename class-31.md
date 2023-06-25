# Reading notes class 31

## [Choosing the State Structure](https://react.dev/learn/choosing-the-state-structure)

**Summarize the five principles for structuring state.**

1. Group related state: Combine multiple state variables into a single variable if they are always updated together.
2. Avoid contradictions in state: Structure the state in a way that prevents conflicting or contradictory pieces of state.
3. Avoid redundant state: If you can calculate information from props or existing state during rendering, don’t duplicate it in the component’s state.
4. Avoid duplication in state: Minimize duplication of data between multiple state variables or within nested objects to maintain consistency.
5. Avoid deeply nested state: Keep the state structure as flat as possible to make updates more convenient.

By following these principles, you can simplify state management, reduce the chance of errors, and ensure that state remains synchronized and efficient.

## [Passing State Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)

**What problem do Contexts aim to solve?**

When passing state deeply with context, contexts aim to solve the problem of prop drilling and make the process of accessing and updating shared state more convenient. Prop drilling occurs when a component needs to pass down state or props to multiple levels of nested components, even if those intermediate components don’t directly use the state or props. So, by using contexts, you can create a centralized state that can be accessed by any component in the component tree, regardless of their position in the hierarchy. This eliminates the need to pass state or props through every level of the tree manually, reducing the complexity and verbosity of the code.

**What is one technique to try before useContext?**

Utilize the prop drilling pattern. Prop drilling involves passing down props from a higher level component to its descendants, allowing them to access and use the data or functions provided. This pattern is a straightforward and simple way to share state or functionality without introducing the complexity of context.

**What hook complements useContext for complex applications?**

The useReducer hook. While useContext allows you to access a shared state across components, useReducer provides a way to manage complex state logic and update that shared state in a predictable manner. The useReducer hook works in conjunction with the reducer pattern, which is a function that takes the current state and an action, and returns a new state based on that action. By using useReducer, you can centralize state management and define the logic for state transitions in a single place.

## Bookmark and Review

[Sharing State Between Components](https://react.dev/learn/sharing-state-between-components)

[Preserving and Resetting State](https://react.dev/learn/preserving-and-resetting-state)

## Things I want to know more about
