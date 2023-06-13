# JavaScript Object Basics

## 1. How would you describe an object to a non-technical friend you grew up with?

 An object is like a virtual version of something in the real world. It has characteristics (like its name, color, or age) and can do things (like bark, run, or play). It helps programmers organize and work with complex pieces of code by grouping related information and actions together.

## 2. What are some advantages to creating object literals?

Object literals are a convenient and efficient way to create objects without the need for complex class structures or constructors. With object literals, you can define properties and their values in a simple and concise manner, making object creation quick and easy. They offer flexibility, allowing you to modify objects as needed, making them ideal for small or one-time-use objects. Object literals also contribute to code readability, as their syntax is clear and easy to understand. Moreover, they are lightweight and efficient, ensuring optimal performance without consuming excessive system resources. Overall, object literals simplify the process of creating and managing objects, enhancing code development and execution.

## 3. How do objects differ from arrays?

Arrays are ordered collections of values, accessed using numeric indices. They are useful for storing a sequence of related items. Objects, on the other hand, are unordered collections of key-value pairs. They represent entities with properties and allow easy access to those properties using keys. Objects are great for organizing and representing data about specific things.

## 4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation

Bracket notation is necessary when accessing an object's property that contains special characters, spaces, or starts with a number. For example, if we have an object with a property named `"property-name"`, we need to use bracket notation `(object["property-name"])` instead of dot notation to access the property.

## 5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

The code defines a dog object with properties like name, age, and color. It also has a method called humanAge. When the method is called, it uses this to refer to the current object, which is the dog. By using this, we can access the dog's properties (like name and age) within the method. This makes the code more flexible and reusable because we don't have to hardcode the object's name; we can use this to refer to the object itself.

```javascript
const dog = {
name: 'Spot',
age: 2,
color: 'white with black spots',
humanAge: function (){
console.log(${this.name} is ${this.age*7} in human years);
}
}
```

# Introduction To The DOM

## 1. What is the DOM?

The DOM (Document Object Model) is a way for web developers to work with web pages. It represents the structure of a web page as a tree-like structure. With the DOM, developers can use languages like JavaScript to change, add, or remove elements on the page, modify styles, handle user interactions, and more. It allows for creating dynamic and interactive web applications.

## 2. Briefly describe the relationship between the DOM and JavaScript

JavaScript and the DOM have a close relationship. JavaScript is a programming language that can be used to interact with and manipulate the DOM. The DOM provides a way to represent a web page's structure, and JavaScript allows developers to change and modify that structure. JavaScript can be used to add or remove elements, update text or styles, respond to user actions, and make web pages more dynamic and interactive.
