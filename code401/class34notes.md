# Reading: API Integration

## Review API Server Build

### Explain the different between a query string parameter and a path parameter.

A **path parameter** is part of the actual path to a specific page or resource. For example, in a website about books, the URL `website.com/books/1` has `1` as a path parameter, which usually refers to a specific book.

A **query string parameter** is added to the end of a URL to filter or adjust the page you're viewing. For example, `website.com/books?genre=fiction` has `genre=fiction` as a query string parameter to show only fiction books.

### What would our API URL with a path id parameter be given the following information:

1. Domain: http://our-site.com
2. v3
3. model name: stuff
4. id: things

http://our-site.com/v3/stuff/things

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

Think of an API interface like a remote control for your TV. You press a button (send a request), and the TV (the API) changes the channel or volume (sends back data or performs an action) based on what button you pressed. It's a way for you to communicate with the TV without needing to know how it works on the inside.

## Review Auth Server Build

### Describe how you would use middleware to implement basic and bearer auth.

Middleware in web development is like a security guard at a club. For **Basic Auth**, when someone comes to the club, the guard asks for their ID and password. If they match the list, they get in. The ID and password are sent with every visit.

For **Bearer Auth**, it's like having a special pass or token. Once you show you're on the list (usually by logging in), you get a token. Then, you just show the token to get in quickly every time.

### Describe the handshake necessary to implement OAuth.

OAuth is like getting a visa to visit a country. First, you ask for permission (you go through the visa application). Then the country checks if you're okay (the service you want to use checks with the OAuth provider if you're allowed). If you get the visa (OAuth token), you can enter the country (use the service) as long as you follow the rules (token's permissions).

The "handshake" is this process of asking, checking, and getting the token to use the service.

### Describe how Role Based Access Control works to a non-technical friend.

Imagine you're at a music festival with different areas: general, VIP, backstage, and performers-only. When you enter, you get a wristband based on what you're allowed to do. If you have a general wristband, you can't go into the VIP area. If you have a VIP wristband, you can go to both general and VIP areas, and so on.

**Role-Based Access Control (RBAC)** is like these wristbands. In a company's computer system, instead of wristbands, people have roles like "employee," "manager," "IT support," and each role has permissions to different parts of the system. An employee can access general info, a manager can access more sensitive reports, and IT support has keys to almost everything to fix problems. It's a way to make sure people can only get into the computer 'areas' they're supposed to.