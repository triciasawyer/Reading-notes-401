# Reading notes class 26

## [React Quick Start](https://react.dev/learn)

**What are the building blocks of a React app?**
Components, JSX, props, and state are the foundation of React JS development.

**What is the difference between an HTML element and a React component?**

- An HTML element is part of the HTML language and represents a specific element in the Document Object Model (DOM). HTML elements are predefined and come with their own default behavior and styling.
- A React component is a reusable, self-contained, and independent unit of UI that can be composed together to build the user interface. They are written in JavaScript and define the behavior, structure, and appearance of a part of the UI.
React components can have their own state and props, allowing for dynamic and interactive UIs.

**What is JSX and why do we use it?**
JSX stands for JavaScript syntax extension. It is a JavaScript extension that allows us to describe React's object tree using a syntax that resembles that of an HTML template. In other words, it is an extension that allows us to write JavaScript that looks like markup and have it returned from a component.

**Describe the process of embedding JavaScript expressions in JSX.**
You can embed JavaScript expressions using curly braces {}. This allows you to dynamically insert values, execute functions, or perform operations within the JSX code.

**Does React or JSX have any special features for iteration or conditional logic?**

**How does React know to respond to a user’s inputs?**
React responds to a user's inputs through the concept of "event handling" and the use of event listeners. Event handling in React involves attaching event listeners to specific elements or components in the user interface. When a user interacts with an element, such as clicking a button or typing in an input field, an event is triggered. React captures these events and executes the corresponding event handler functions to respond to the user's input.

**What word indicates that a React component manages data with a Hook?**
"UseState"

**How can two react components share data?**
Two React components can share data by lifting the state up to their closest common ancestor component. This means that the shared data is stored in a common parent component, and then passed down to the child components as props.

## [Render and Commit](https://react.dev/learn/render-and-commit)

**What are the three steps of refreshing a React UI?**
Modifying state or props, performing reconciliation, and rendering, which allows for the React UI to be refreshed to reflect the updated data and provide an interactive user experience.

**How do you trigger updates to a component after the initial render?**
When you update your component's state using the set function, it automatically triggers a re-render. You can think of this process as a restaurant guest ordering tea, dessert, and various items after placing their initial order. The guest's subsequent orders depend on their level of thirst or hunger, which corresponds to the state of the component. React's state updates work in a similar way, allowing you to dynamically modify the component's data and trigger a re-render to reflect those changes.

**Does React recreate DOM nodes on every rerender?**
No, React does not recreate DOM nodes on every re-render. React utilizes a virtual DOM (VDOM) concept to efficiently update the actual DOM. It compares the previous virtual DOM representation with the new one. It identifies the differences between the two representations, and updates them, which is known as the "diffing" process. By doing so, it allows React to optimize rendering by avoiding unnecessary recreation of DOM nodes. Instead, it focuses on efficiently updating the existing DOM nodes to reflect the changes in the component's state or props.

**After React has updated the DOM, what still needs to happen before the user sees the change?**
After the DOM updates are applied, the browser performs the layout and paint phases. During the layout phase, the browser calculates the position and size of each element in the DOM tree. Then, in the paint phase, the browser renders the updated content on the screen. Then, the updated content becomes visible to the user on the screen. The user can now see the changes that were made to the UI as a result of React's rendering and DOM update process.

## Bookmark and Review

[Your First Component](https://react.dev/learn/your-first-component)

[Importing and Exporting Components](https://react.dev/learn/importing-and-exporting-components)

[Writing Markup with JSX](https://react.dev/learn/writing-markup-with-jsx)

[sass cheatsheet](https://devhints.io/sass)

[react cheatsheet](https://devhints.io/react)

## Additional Questions

**Note the naming conventions in the Airbnb React/JSX Style Guide. What pattern(s) do you see?**
Be sure to return a value in your render methods.

**Looking ahead at this module’s course schedule, What do you look forward to learning?**
I am excited to learn about hooks in general and what they do/how they work.

**What are your learning goals after reading and reviewing the class README?**
I have heard of SASS a lot and I am excited to learn about that extension.

## Things I want to know more about
