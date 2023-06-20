# Reading notes class 28

## [useEffect hook](https://react.dev/reference/react/useEffect#reference)

**What is the main intended use case for the useEffect hook?**
It is primarily used for handling side effects in functional components. It allows you to perform actions such as fetching data, subscribing to events, or manipulating the DOM after the component has rendered. useEffect is designed to handle these side effects in a clean and declarative manner, ensuring they are executed at the appropriate times during the component’s lifecycle.

**How does the effect’s logic interact with the component?**
The effect’s logic interacts with the component by running after each render, with the ability to clean up before subsequent renders or when the component unmounts.

**What is the importance of the return value from the effect’s logic function?**
It allows you to specify a cleanup function that will be executed when the component unmounts or before the effect runs again. By doing so, you can perform necessary cleanup tasks, such as unsubscribing from event listeners, cancelling timers, or disposing of resources. This helps prevent memory leaks and ensures that any unnecessary or lingering effects are properly cleaned up when they are no longer needed.

## Bookmark and Review

[Responding to Events](https://react.dev/learn/responding-to-events)

[Conditional Rendering](https://react.dev/learn/conditional-rendering)

[Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)

[Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

## Reflection

**What are your learning goals after reading and reviewing the class README?**
Just to get some experience and understanding of Hooks.

## Things I want to know more about
