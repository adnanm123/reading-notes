# Reading: Bearer Authorization

## Intro to JWT

## What is a JSON Web Token (JWT)?

A JSON Web Token (JWT) is a secure way to package and transmit information, often used in web applications. It's like a digital ID card that proves who you are and what you're allowed to do online.

## When should we use JSON Web Tokens?

Use JSON Web Tokens (JWTs) when you want a secure and compact way to handle user authentication, authorization, and data exchange in web applications and APIs. They're like digital ID cards that prove who you are and what you can do online.

## Claims are expected in which structural component of a JWT?

Claims are expected in the "Payload" component of a JSON Web Token (JWT). The JWT consists of three main parts: the Header, the Payload, and the Signature. Claims are statements or assertions about the subject (typically, the user) and additional data, and they are included in the Payload. The Payload contains both registered claims (predefined by the JWT standard) and custom claims (defined by the application). These claims provide information about the user's identity, authorization, or other related data.

## Are JWTs Secure?

## If I get a JWT and I can decode the payload, how can we call that secure?

A JSON Web Token (JWT) is like a sealed envelope. While you can read what's inside (the payload), you trust that it hasn't been tampered with because it has a digital seal (the signature) and is sent through a secure channel. So, the security comes from the seal, not the content inside the envelope.

## If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

When sending a JSON Web Token (JWT), both the sender and receiver must know a secret key, like a shared password. This key is used to ensure the JWT's integrity, like sealing an envelope. It's important to keep this key safe, as it's used to verify the JWT's authenticity.

## Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

Sending concatenated content and a secret securely is like putting a secret message in a locked box. You give the locked box (with the message inside) to the recruiter. To open the box and read the message, they need a special key, which only you and the recruiter know. This way, no one else can read the message, ensuring it stays private during delivery. It's like having a secret code for a private message.

## JWTs Explained

## Why use JWT?

Use JSON Web Tokens (JWTs) for secure user identification, permissions, and efficient communication between parts of a web application. They're like digital ID cards that help ensure that users are who they claim to be and dictate what they can do in the app.

## JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

Think of a JWT like a tiny, digital passport for your identity in a computer system. It's compact, which means it's small and easy to carry around. But the cool part is that it's like a mini ID card that carries all the important information about you, like your name and what you're allowed to do. This way, you don't need to carry a big file of information with you all the time. It's like having a small, self-contained package that proves who you are and what you can access in a secure way.

## What are the three components (the structure) of a JWT signature?

A JWT signature has three parts:

1. The header (like a title).
2. The payload (the actual content, like your name).
3. The signature (a seal to make sure it's not tampered with).

## Reflection

## What are your learning goals after reading and reviewing the class README?

Becoming a better coder!
