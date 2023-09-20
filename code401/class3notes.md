# Readings: Express REST API

## Review: ES6 Classes

## Classes are a template for creating ____.

objects

## Can a class declaration be hoisted?

In JavaScript, class declarations are not hoisted, which means you cannot use a class before it's defined in your code. Unlike functions, classes must be declared before they are used.

## How would you describe a constructor and contextual “this” to a non-technical friend?

**Constructor:**
A constructor is like a blueprint for making something in programming. It tells the computer how to create an object with specific features.

**Contextual "this":**
"this" is like a pointer that helps the computer figure out which object it's currently working with. It's like saying, "I want to do something with this particular thing, not some other thing."

## Using Express Routing

## Within Express, what does routing refer to?

In Express, routing is like giving directions to your web application. It tells the app what to do when someone visits a specific web address (URL). So, it's like guiding the traffic on your website to the right places.

## What is the difference between a route path and a route method?

* **Route Path:** This is like the address or location on a website. It tells the server where to go when someone visits a specific web address (URL), like "/products" or "/users/:id".

* **Route Method:** This is like the action you want to perform at that location. It tells the server what to do when someone visits that web address, like "GET" to fetch data or "POST" to submit data.

So, route path is where, and route method is what you do there on a website or web application.

## When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?

You add `next` as a parameter to a route handler or middleware in Express when you want to tell Express to move to the next step in handling a request. It's like saying, "Okay, I've done my part, now let's move on to the next thing." If you don't call `next()`, Express won't know to move forward, and the request might get stuck. So, when you see `next` as a parameter, it's a way to control the flow of your application.

## Express Routing

## What is an Express Router?

An Express Router is like a folder for your routes in an Express.js application. It helps you neatly organize and group related routes together, making your code easier to manage. Think of it as a way to keep your routes tidy and organized, just like you'd organize files into folders on your computer.

## By what mean do we initialize express.Router() in an express server?

To initialize an Express Router in an Express server, you create a new instance of the router using the code `const router = express.Router();`. It's like creating a new folder to group related routes together in your server.

## What do we use route middleware for?

Route middleware in Express is like a helper that can do extra tasks before or after handling a request. It's useful for things like checking if a user is logged in, making sure data is correct, or keeping track of what's happening in the server. It's like having a little assistant to make sure everything goes smoothly with your web application.

## Reflection

## What are your learning goals after reading and reviewing the class README?

Learning the fundamental concepts of SQL, such as how to create and manage databases, tables, and relationships.
