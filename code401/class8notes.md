# Reading: Access Control (ACL)

## 5 steps to RBAC

## What is Role Based Access Control (RBAC) and why do we care?

Role-Based Access Control (RBAC) is a method to manage who can do what in a system based on their job roles. We care about RBAC because it helps us control and restrict access to sensitive information and functions, reducing security risks and ensuring that people only have access to what they need to do their jobs. It simplifies user management and compliance with regulations, making it easier to protect data and maintain a secure environment.

## Describe a Role/Permission heirarchy that you might implement using RBAC.

1. **Role: User**

* Permissions:
  * Upload files: Allows users to upload files to their own folders.
  * Download files: Permits users to download files from their own folders.
  * Create folders: Enables users to create folders within their own directories.

2. **Role: Manager**

  * Permissions:
    * All permissions of the User role.
    * Manage user permissions: Allows managers to grant or revoke permissions for other users.
    * Delete files: Permits managers to delete files from their own folders.

3. **Role: Admin**

* Permissions:
  * All permissions of the Manager role.
  * Manage users: Allows admins to create, modify, or delete user accounts.
  * Manage groups: Enables admins to create and manage user groups.
  * Delete folders: Permits admins to delete folders, including those of other users.

## What approach might you take to implement RBAC?

1. **Identify Roles:** Determine the different roles that exist in your system or organization. Roles should represent groups of users with similar responsibilities.

2. **Assign Permissions:** Define what actions or permissions each role should have. Specify what each role is allowed to do within the system.

3. **Associate Users with Roles:** Assign individual users to the appropriate roles based on their job functions and responsibilities.

4. **Implement Access Control:** In your software or application, enforce access control based on the roles and permissions assigned to users. Ensure that users can only perform actions allowed by their roles.

5. **Regularly Review and Update:** Periodically review and update roles and permissions to accommodate changes in the organization or system. Remove or adjust access as needed.

## wiki - RBAC

## If Authentication is “you are who you say you are,” what is Authorization?

Authorization, in simple terms, means "what you're allowed to do." It decides whether you have permission to access certain resources or perform specific actions within a system or application after your identity has been confirmed through authentication.

## Name three primary rules defined for RBAC.

1. **Role Assignment Rule:** This rule determines which roles are assigned to users based on their job functions. Users are grouped into roles, like "Employee," "Manager," or "Admin."

2. **Permission Assignment Rule:** This rule specifies what actions or permissions each role is allowed to perform. For example, the "Employee" role may have permission to view documents, while the "Manager" role can edit them.

3. **Access Control Rule:** This rule controls whether a user with a particular role and its associated permissions can access a specific resource or perform an action. It enforces the RBAC policies, ensuring users can only do what their roles allow.

## Describe RBAC to a non-technical friend.

RBAC, which stands for Role-Based Access Control, is a way of controlling who can do what in a system. Think of it like a school with different roles: students, teachers, and the principal.
Each role has its own set of rules. For instance, students can't decide the school's budget, but the principal can. RBAC helps make sure that people can only do the things that make sense for their role, which keeps everything organized and secure.

## RBAC tutorial

## What Are access rights Associated with? The User? or The Role? Explain.

Access rights in Role-Based Access Control (RBAC) are associated with Roles, not individual Users.

Think of it like this: In a school, students, teachers, and the principal each have specific roles. These roles come with certain rights or permissions. For example, teachers can enter the teachers' lounge, students can't.

So, access rights are linked to roles. When someone takes on a role, they automatically get the rights associated with it. This makes it easier to manage who can do what in a structured and efficient way.

## Access Rights, or Authorization, is activated after a user successfully does what?

Access Rights, or Authorization, are activated after a user successfully completes the process of Authentication.

## Explain how RBAC might benefit a business.

RBAC benefits a business by simplifying access management and boosting security. It ensures that the right people have the right access to resources, reduces errors, and helps meet regulatory requirements, all while adapting to the company's growth.

## Reflection

## What are your learning goals after reading and reviewing the class README?

Tring to become a better developer.
