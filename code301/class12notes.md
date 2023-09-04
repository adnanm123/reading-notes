# Status Codes Based On REST Methods

## In your own words, describe what each group of status code represents:

**100's (Informational):**

These codes provide information but don't say if things went well or not. They're like a message saying, "I got your request, let's talk more."

**200's (Success):**

These codes mean everything went as planned. It's like the server saying, "Got it! Here's what you asked for."

**300's (Redirection):**

These codes tell you to go somewhere else. Imagine a sign on the road saying, "The place you want is down the street."

**400's (Client Errors):**

These codes mean there's a problem with what the user did. It's like saying, "Oops, you made a mistake."

**500's (Server Errors):**

These codes mean the server messed up, not the user. It's like the server saying, "My bad, something went wrong on my end."

## What is a status code 202?

HTTP status code 202, "Accepted," means the server got your request and will work on it, but it's not finished yet. It's like when you order food for delivery, and they tell you, "We got your order; it's on the way, but it's not at your door yet."

## What is a status code 308?

HTTP status code 308 means, "The thing you're looking for moved to a new place, and you should always go there now." It's like when someone changes their home address, and they say, "I moved permanently; please come to my new address from now on."

## What code would you use if an update didn’t return data to a client?

If an update didn't give any data back to the client but it worked fine, you'd use HTTP status code 204, which means, "It worked, but there's nothing special to see here." It's like telling someone, "I did what you asked, but there's no extra news to share."

## What code would you use if a resource used to exist but no longer does?

If something that was once available on a website is now completely removed and won't come back, you'd use HTTP status code 410, which means, "It used to be here, but it's gone forever, and there's no replacement." It's like saying, "That item on the menu is no longer offered, and it won't be back."

## What is the ‘Forbidden’ status code?

The "Forbidden" status code, which is HTTP code 403, means "No entry allowed." It's like being told, "You can't go there; it's off-limits to you."

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Putting the MongoDB database connection string in a `.env` file is like locking a valuable item in a hidden safe. It's a security measure because it makes it hard for others to access the sensitive connection details. This approach offers practical benefits, too. You can create different `.env` files for various situations, simplifying configuration management. When changes are needed, you can adjust the `.env` file without changing your code, making deployment and updates smoother. In collaborative projects, team members can have their own `.env` files, avoiding conflicts. As your project expands, using a `.env` file allows for flexible changes without causing complications.

## What is middleware?

Middleware is like a helpful assistant in web development. It sits between the user's request and the server's response and does important tasks like checking if a user is logged in, processing data, or keeping track of what's happening. It's like having someone who organizes things before you see the final result, making web applications work better and more securely.

## What does `app.use(express.json())` do?

Certainly, app.use(express.json()) is like a magic decoder for your server. When a client sends data in JSON format, this line of code helps the server understand it by turning it into a format the server can use, just like translating a secret code into plain language. This is super handy when you want your server to process JSON data from client requests, like when you're building web applications or APIs.

## What does the `/:id` mean in a route?

Certainly, think of `/:id` in a route like a blank space waiting to be filled. It's a way to capture specific information from the URL. For example, `/users/:id` means you can put different numbers or IDs in that blank space, like `/users/1`, `/users/42`, or `/users/123`. It helps your server figure out which user you're talking about in the URL.

## What is the difference between `PUT` and `PATCH`?

**PUT** replaces the entire resource with new data, while **PATCH** makes partial updates by changing only specific parts of the resource.

## How do you make a default value in a schema?

To set default values in a schema, you just tell it what values to use if no value is provided. It's like saying, "If someone doesn't specify a name, use 'John' as the default. And if they don't provide an age, set it to 30 by default."

## What does a `500` error status code mean?

A 500 error is like when a website crashes, and you see a message saying, "Sorry, something went wrong." It means there's a problem on the server's side, but it doesn't say exactly what the problem is. It's like saying, "My bad, I messed up."

## What is the difference between a status `200` and a status `201`?

The difference between a status code 200 and 201 in HTTP responses is straightforward. When you see "200 OK," it means the server found what you asked for and is giving it to you. It's like saying, "Here it is." In contrast, "201 Created" not only says, "Here it is," but also adds, "By the way, I made something new just for you based on your request." So, it confirms that a new resource has been created as a result of your request.
