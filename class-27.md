# Reading notes class 27

## [Thinking in React](https://react.dev/learn/thinking-in-react)

**Summarize the five steps of thinking in react.**

1. Break the UI into a component hierarchy: Analyze the user interface and break it down into smaller, reusable components. Identify the components that represent distinct parts of the UI and their relationships with each other.
2. Build a static version of the UI: Create a static version of the user interface using the components identified in the previous step. This static version does not have interactivity or state yet and serves as a visual representation of how the UI should look.
3. Identify the minimal (but complete) representation of UI state: Determine the minimal set of state that the UI needs to work correctly. Focus on identifying the state that affects the UI’s behavior and appearance.
4. Identify where the state should live: Determine which component(s) should own and manage the identified state. Identify the common ancestor component that can store and pass the state as props to the necessary child components. Consider the component that needs the state to render correctly.
5. Add inverse data flow: Establish two-way communication between components by adding event handlers and updating the state based on user interactions. Ensure that changes in the UI trigger state updates and that the updated state is propagated down the component hierarchy as needed.

## [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)

**What is one reason a local variable isn’t sufficient for managing a React component?**

Local variables only exist within the scope of the function or block where they are defined. In React, components often need to maintain and update their state across multiple render cycles and handle user interactions. Using local variables alone would not provide a persistent and reliable way to store and update component state. React components require a mechanism to preserve state across renders, handle state updates, and trigger re-renders when necessary. This is where React’s built-in state management, such as the useState hook or class-based component state, comes into play. It allows components to manage and update state effectively throughout their lifecycle.

**What is the argument to the useState hook, and what are the two parts of its return array?**

The argument is the initial state value, and the two parts of its return array is first, the  current state value, which can be accessed and updated throughout the component’s lifecycle. Then second, a function that allows you to update the state. This function is commonly named with a “set” prefix followed by the state variable name, such as setState. When invoked, it triggers a re-render of the component with the updated state value.

**How can Component A access state from Component B?**

You can lift the state up to a common ancestor of those components. This way, the shared state can be accessed by both Component A and Component B.

## Bookmark and Review

[Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)

[Rendering Lists](https://react.dev/learn/rendering-lists)

[State as Snapshot](https://react.dev/learn/state-as-a-snapshot)

[useState hook](https://react.dev/reference/react/useState)

## Reflection

**What are your learning goals after reading and reviewing the class README?**

To get refreshed with react content and understand/get comfortable with the use of the state hook for functional components.

## Things I want to know more about
