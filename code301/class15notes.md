# What is OAuth

## What is OAuth?

OAuth (Open Authorization) is an open-standard authorization framework that allows unrelated websites and services to grant secure access to their resources without sharing the initial login credentials. It simplifies user experiences and enhances security by enabling seamless single sign-on (SSO) across different online platforms.

## Give an example of what using OAuth would look like.

Imagine you want to log in to a website, and instead of creating a new account or entering your credentials, you see a "Log in with Google" button. By clicking it, the website uses OAuth to securely authenticate you with your Google account without ever knowing your Google password. This way, you can access the website without creating a new account or sharing your Google login information.

## How does OAuth work? What are the steps that it takes to authenticate the user?

1. **User Authentication**: The user logs in to a website or service (the authorization provider) using their credentials.

2. **Initiating Access**: The user wants to access another website or service (the target service) without providing separate login credentials.

3. **Request Token**: The authorization provider generates a one-time token and a secret unique to this transaction.

4. **Client Software**: The user's client software (e.g., a browser) receives the token and secret.

5. **User Approval**: The user may be asked to approve the authorization request to the target service.

6. **Access Token**: After approval, the user receives an approved access token.

7. **Access Granted**: The user provides this access token to the original website, which uses it to access the target service on their behalf.

8. **Transaction Complete**: The user sees a successful transaction, all without needing to log in again.

## What is OpenID?

OpenID is a technology related to OAuth but with a focus on authentication rather than authorization. OpenID allows users to use a single set of credentials to log in to multiple websites. It serves as a single sign-on (SSO) solution, vouching for users' identities. OAuth is primarily about granting access, while OpenID is about verifying a user's identity for authentication purposes. OAuth and OpenID often work together to provide a seamless and secure user experience across different online platforms.

## Authorization and Authentication flows

## What is the difference between authorization and authentication?

**Authentication** is the process of verifying the identity of a user or system, typically through a username and password, biometric data, or other credentials.
**Authorization** is the process of granting or denying access to specific resources or actions based on the authenticated user's permissions and privileges.

## What is Authorization Code Flow?

The **Authorization Code Flow** is an OAuth 2.0 flow used for regular web applications. It allows secure authentication by exchanging an Authorization Code for an access token. This flow is suitable for server-side applications where the source code is not publicly exposed.

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

**Authorization Code Flow** with PKCE is an enhanced version of the Authorization Code Flow. It is designed for mobile, native, and single-page applications that require additional security. It uses a Proof Key for Code Exchange (PKCE) to mitigate certain security threats during authentication.

## What is Implicit Flow with Form Post?

The **Implicit Flow with Form Post** is an alternative OAuth 2.0 flow.
It is intended for Public Clients or applications that can't securely store Client Secrets. When used with Form Post response mode, it provides a streamlined workflow for user authentication. Typically used when an application needs only an ID token for user authentication.

## What is Client Credentials Flow?

The **Client Credentials Flow** is used for machine-to-machine (M2M) applications like CLIs, daemons, or backend services. Instead of user authentication, it authenticates and authorizes the application itself. This flow is suitable for scenarios where traditional authentication methods, such as username and password, don't apply.

## What is Device Authorization Flow?

The **Device Authorization Flow** is used for devices with limited input capabilities that connect to the internet. It doesn't directly authenticate the user but asks the user to authorize the device using another device like a computer or smartphone. Offers a user-friendly experience for devices without text input.

## What is Resource Owner Password Flow?

The **Resource Owner Password** Flow is used by highly-trusted applications.
It requests users to provide their credentials (username and password) directly through an interactive form.
This flow should be used sparingly and only when other redirect-based flows are not feasible.
