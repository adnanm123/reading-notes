# React Native & Expo Reading Assignment

## Core Components of React Native

### What are three Core Components of React Native and describe what they do?

1. **View**: A container that supports layout with flexbox, style, touch handling, and accessibility controls, acting as the building block for UI.
2. **Text**: A component for displaying text which can be styled and nested within other components like `View`.
3. **Image**: Used for displaying images from local and remote sources, with support for various styling options, such as resizing.

## React Native

### What problem does React Native solve (why call it native)?

React Native allows developers to build mobile applications using JavaScript and React, with a true native user interface. It compiles to native app components, which makes it possible for developers to write mobile apps that have the performance and look and feel of a native application but using web development principles.

### What are the building blocks of a React Native app? How does that compare to a React app?

The building blocks of a React Native app are components that correspond to native UI components, such as `View`, `Text`, and `Image`. In contrast, a React app is built with components that ultimately render to HTML elements for the web.

## Expo

### What solution does Expo provide?

Expo provides a platform and a set of tools for developers to build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.

### Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.

Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the **managed workflow**.

### What is the difference between React Native and Expo?

React Native is an open-source framework for building native apps with JavaScript, while Expo is a set of tools and services that sit on top of React Native to help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.

## Expo Snack

### Checkout this tool. What does Snack allow you to do?

Snack is an online editor provided by Expo that allows you to write React Native code and preview the results live on your device or in a simulator/emulator in the browser. It's great for quick prototyping and sharing examples.

## Ejecting

### What does “eject” mean within the context of Expo?

"Ejecting" within the context of Expo refers to taking an app out of the managed workflow and into the bare workflow, giving you full control over the native projects and dependencies.

### When should you not eject?

You should not eject if you are not ready to handle native iOS and Android development, as it adds complexity to your project and requires you to manage native code.

### Why might you choose to eject?

You might choose to eject if you need functionality that Expo does not support out of the box, like specific native modules or custom native code, or if you need to integrate with a custom native app.
