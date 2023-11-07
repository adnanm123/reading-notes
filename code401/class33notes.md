# Reading: `<Login />` and `<Auth />`

## What is Role Based Access Control (RBAC)?

### What is Role Based Access Control (RBAC)?

Role-Based Access Control (RBAC) is a system where access to resources and operations is granted based on the roles assigned to users rather than individual user identities.

### Share some an example of RBAC including all possible CRUD operations and correlating roles.

* **Admin Role:** Can Create, Read, Update, and Delete any article, and manage user roles.
* **Editor Role:** Can Create, Read, and Update any article but cannot Delete.
* **Author Role:** Can Create and Read articles; Update and Delete only their own articles.
* **Visitor Role:**  Can only Read articles.

### What are the Benefits of RBAC?

1. **Simplified Management:** Assigning and updating user access becomes easier by just updating roles rather than individual user permissions.
2. **Enhanced Security:** Limits the exposure of sensitive operations or data to only those with a valid need.
3. **Scalability:** As the organization grows, roles can be easily expanded or modified without overhauling the whole system.
4. **Improved Compliance:** Helps organizations meet regulatory requirements by ensuring only authorized personnel can access specific data.
5. **Reduced Administrative Work:** With roles in place, new users can be quickly onboarded with the right set of permissions.

## react-cookie library vs. react-cookies component

### Describe some react-cookie features.

1. Easy API to set, get, and delete cookies.
2. Server-side rendering support.
3. Cookie change listeners to detect updates.
4. Integration with React's context API for better state management.

### Describe some react-cookies features.

1. Simplified methods to manage cookies in React apps.
2. Hooks for cookie management.
3. Cookie provider to maintain cookie state across the application.

### Which library would you prefer would you prefer? Why?

I would prefer "react-cookie" because it provides a more comprehensive set of features, including server-side rendering support and cookie change listeners, which can be crucial for larger applications or platforms that need enhanced functionality and responsiveness.
