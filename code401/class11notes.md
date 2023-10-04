# Readings: Socket.io

## Web Sockets

## What is a Web Socket?

A WebSocket is a technology that enables real-time communication between a web browser (or any client) and a server over a single, long-lived connection. It allows information to be sent back and forth instantly without the need for continuous requests, making it ideal for interactive and real-time applications like chat and online games.

## Describe the Web Socket request/response handshake and what happens once the connection is established.

In simple terms, the WebSocket handshake is like the initial introduction between two people before they start chatting. Once the handshake is done and they are acquainted, they can have a conversation freely without waiting for each other's turn. They can keep talking until one of them says, "Let's end the conversation," at which point they both agree to say goodbye.

## Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

Web Sockets provide a standardized way for the server to send content to a client without first receiving a request (or a "prompt") from that client. This is in contrast to traditional HTTP communication, where the client initiates communication by sending a request to the server, and the server responds with content. WebSocket allows the server to initiate communication and send data to the client at any time without waiting for a client request.

## Socket.io Tutorial

## What does the event handler `io.on()` do?

`io.on()` is an event handler in Socket.io that listens for incoming connections from clients. When a client connects to the server, the code inside `io.on('connection', callback)` is executed. It's like saying, "When a client connects, do this."

## Describe some possible proof of life or proof that the code works as expected

A common proof of life is seeing log messages in the console. For example, when a client connects to the server, you can log a message like "Client connected" in the server's console. Additionally, successful data exchanges between the client and server, like sending and receiving messages, are also proof that the code is working as expected.

## What does socket.emit() do?

`socket.emit()` is used to send a message or data from the server to a specific client. It's like the server saying, "Hey, client, here's some information for you." The client can then listen for this event and handle the data sent by the server.

## Socket.io vs Web Sockets

## What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

WebSocket is a communication protocol, while Socket.IO is a library built on top of WebSocket. It's like the difference between a road (WebSocket) and a car (Socket.IO) that runs on the road. WebSocket provides the basic infrastructure for real-time communication, while Socket.IO adds features and simplifies WebSocket usage, making it easier to work with.

## When would you use Socket.IO?

You would use Socket.IO when you want to implement real-time, bidirectional communication between a server and multiple clients in a web application. Socket.IO is great for chat applications, online gaming, live notifications, and any scenario where instant data updates are needed.

## When would you use WebSockets?

You would use WebSockets when you need a low-level, efficient, and standardized protocol for real-time communication. WebSockets are ideal when you want to create custom real-time features in your application without relying on a specific library like Socket.IO. It's a good choice for scenarios where you need fine-grained control over the communication protocol.
