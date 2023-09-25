# Readings: Authentication

## Securing Passwords

## Explain to a non-technical friend how you would safely hash and store a password.

Think of hashing your password like turning it into a secret code that only the website understands. They keep this secret code instead of your real password, so even if someone tries to steal it, they won't know your actual password. It's like a double layer of protection!

## What is Bcrypt?

Bcrypt is a security tool used to protect passwords. It takes a password and turns it into a scrambled code that's really hard to unscramble. This way, even if someone gets access to the stored codes, they won't easily know the actual passwords. Bcrypt is like a guardian for your passwords, keeping them safe from bad guys.

## Why might you use something like Bcrypt?

You would use Bcrypt or similar password hashing algorithms to securely store and protect passwords in a way that makes it extremely difficult for attackers to decipher them. Bcrypt is designed to be slow and computationally intensive, which helps thwart brute force and dictionary attacks. It also incorporates a salt, which adds randomness to each hashed password, making it even more challenging for attackers to crack passwords using precomputed tables or rainbow tables. Essentially, Bcrypt enhances the security of user passwords stored in databases, helping to safeguard user accounts from unauthorized access in case of a data breach.

## Basic Auth

## What is Basic Authentication?

Basic Authentication is like a username and password lock on a website. You enter your username and password, and it lets you in if they are correct.

## What properties are necessary in the header of a Basic Auth request?

In simple terms, you might use something like Bcrypt to securely store passwords. Bcrypt is a tool or algorithm used in software development to take a password and turn it into a long, complex, and encrypted version that's difficult for attackers to decode. This helps keep user passwords safe and prevents unauthorized access to accounts. It's like putting your password in a super-secret vault that only you can open, making it much harder for anyone else to figure out what your password is.

## How are `username:password` in Basic Auth encoded?

In Basic Authentication, the "username:password" combination is encoded using Base64 encoding. Here's a simple explanation of the process:

1. You take the "username:password" combination, for example, "myUsername:myPassword".

2. You encode this combination into Base64 format. In this example, it would become "bXlVc2VybmFtZTpteVBhc3N3b3Jk".

3. This Base64-encoded string is then included in the HTTP request's "Authorization" header. The header typically looks like this:

Authorization: Basic bXlVc2VybmFtZTpteVBhc3N3b3Jk

## OWASP auth cheatsheet

## Define the authentication process to a non-technical recruiter.

Authentication is like a digital key that lets you access certain online services. When you log in to a website or app, you're proving that you're the person you claim to be. It's a bit like showing your ID to get into a restricted area, but it happens online. Once you've proven your identity, you get access to the services or information you need.

## How should your error messaging respond (both HTTP and HTML)? Why?

Error messaging should be clear and informative to help users understand issues and take appropriate actions. It also aids developers in troubleshooting and improving system reliability. Providing generic error messages to users while logging more detailed error information for developers is a common practice to balance user-friendliness with debugging capabilities.

## Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

okay

## Additional Questions

## Looking ahead at this module’s course schedule, What do you look forward to learning?

Everything

## What are your learning goals after reading and reviewing the class README?

Becoming a better coder
