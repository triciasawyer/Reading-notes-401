# Reading notes class 43

## [getting started with react native](https://reactnative.dev/docs/getting-started)

**Name three Core Components of React Native and describe what they do.**

- View: The View component is like a container that provides a way to structure and style content within a screen. It is similar to the `<div>` element and represents a rectangular area on the screen. It's used to group and layout other components, apply styles, and handle touch events.
- Text: The Text component is used for displaying text content on the screen. It's similar to the `<p>` or `<span>` elements in HTML and supports styling, formatting, and handling user interactions. It can display text as plain text, formatted text, or text retrieved from variables or API responses (static and dynamic text).
- Image: The Image component is used to display images in a React Native application and it allows you to load and display local or remote images, providing features like resizing, scaling, and caching. It's similar to the <img> element in HTML and supports various image formats and sources.

**What problem does React Native solve (why call it native)?**

React Native solves the problem of developing mobile apps for multiple platforms (iOS, Android) using a single codebase. The Native in React Native refers to the ability to build native mobile apps using JavaScript and React, leveraging the platform-specific UI components and APIs.

**What are the building blocks of a React Native app? How does that compare to a React app?**

The building blocks of a React Native app are similar to those of a React app, except for the fact that they have platform-specific implementations.

A key difference between each is that with React web apps, the components are rendered into the HTML DOM (Document Object Model) provided by the browser. On the other hand, React Native components are rendered into platform-specific UI components provided by the underlying mobile operating system, such as UIView for iOS and View for Android. 

## [expo](https://expo.dev)

**What solution does expo provide?**

Expo is a set of tools, libraries, and services that provides a solution for developing and building React Native applications more easily. It offers a variety of features and benefits to simplify the development process

**Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.**

Managed

**What is the difference between React Native and Expo?**

React Native is the framework that enables building mobile apps with JavaScript and React, while Expo is a set of additional tools and services that simplify the development process and provide extra features and capabilities. You can think of Expo as an extension or enhancement of React Native, making it easier to build and deploy React Native apps.

## [expo snack](https://snack.expo.dev/)

**Checkout this tool. What does snack allow you to do?**

## [ejecting](https://docs.expo.dev/archive/glossary/#eject?redirected)

**What does “eject” mean within the context of Expo?**

Eject refers to the process of transitioning from the Expo managed workflow to the bare workflow. When you eject an Expo project, you are basically converting it into a standard React Native project. This means you will have full access to the underlying native code and configuration files, allowing you to customize and configure your app more extensively. Ejecting is typically done when you need to add native modules, modify native code, or have more control over the build process.

**When should you not eject?**

- If your apps functionality can be achieved using the Expo tools and available libraries without the need for extensive customization or access to native modules, you should just stay within the managed workflow.
- Ejecting can be complex to the development process because with ejecting, you'll need to handle native dependencies, build configurations, and potential platform-specific issues yourself. If you want faster development iterations and want to focus more on the JavaScript side of your app, stick with the managed workflow.

**Why might you choose to eject?**

- You may want access to the native functionality and all the built-in features and APIs to gain direct access to the native code of your app.
- If you want to optimize your apps performance by fine-tuning the native code, leveraging platform-specific optimizations, or integrating low-level optimizations that are not available in the managed workflow.

## Tutorial

[react native basics](https://reactnative.dev/docs/tutorial)

## Bookmark and Review

[react native](https://reactnative.dev/)

## Additional Questions

**Looking ahead at this module’s course schedule, What do you look forward to learning?**

I am looking forward to project kickoffs and getting that going

**What are your learning goals after reading and reviewing the class README?**

My learning goals are to take as much knowledge taught as I can, about react native and all the features that come along with it
