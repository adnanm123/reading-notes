# API Design Best Practices

## What does REST stand for?

Representational State Transfer

## REST APIs are designed around a ____.

Resources

## What is an identifier of a resource? Give an example.

An identifier of a resource is a unique and specific way to address and distinguish a resource in a system, typically within the context of a RESTful API. It's used to uniquely identify a particular resource, allowing clients to request, manipulate, and interact with that resource. For example, the URI for a particular customer order might be:

`https://adventure-works.com/orders/1`

## What are the most common HTTP verbs?

GET, POST, PUT, PATCH, and DELETE

## What should the URIs be based on?

URIs in a RESTful API should be based on the things you want to work with, like items in a store or user profiles. Just like web addresses, these URIs help your app find and manage those things. Resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

## Give an example of a good URI.

`https://adventure-works.com/orders`

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

A "chatty" web API is when you need to ask the server lots of tiny questions, one at a time. This is not good because it takes more time and can make things slow. It's better to ask the server bigger questions all at once to get more done quickly.

## What status code does a successful `GET` request return?

A successful GET method typically returns HTTP status code 200 (OK).

## What status code does an unsuccessful `GET` request return?

If the resource cannot be found, the method should return 404 (Not Found).

## What status code does a successful `POST` request return?

If a POST method creates a new resource, it returns HTTP status code 201 (Created).

## What status code does a successful `DELETE` request return?

If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content), indicating that the process has been successfully handled, but that the response body contains no further information.
