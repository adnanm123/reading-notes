# Local Storage and How To Use It On Websites

## 1. Why would a developer use local storage for a web application?

Developers use local storage for web applications to store data on the client's browser, providing persistent storage even after the user closes the browser. It allows for offline functionality, improved performance by reducing server requests, and enables personalized experiences for users.

## 2. What information should not be stored in local storage?

Sensitive information such as passwords, credit card details, and personally identifiable information should not be stored in local storage. It is important to avoid storing any data that could compromise user privacy or security. Instead, such sensitive information should be securely transmitted and stored on server-side databases with appropriate encryption and protection measures.

## 3. Local storage can store what type of data? How would you convert it to that type before storing?

Local storage can store data as strings. To store non-string data such as objects or arrays, you need to convert them to strings using serialization methods like JSON.stringify(), and when retrieving, parse the string back into its original data type using JSON.parse() or similar techniques.
