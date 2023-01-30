# Class 15

## What is OAuth

1. **What is OAuth?:** OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

2. **Give an example of what using OAuth would look like.:** For example, you can tell Facebook that it's OK for ESPN.com to access your profile or post updates to your timeline without having to give ESPN your Facebook password.

3. **How does OAuth work? What are the steps that it takes to authenticate the user?:** 

```
  Step 1 – The User Shows Intent.
  Step 2 – The Consumer Gets Permission.
  Step 3 – The User Is Redirected to the Service Provider.
  Step 4 – The User Gives Permission.
  Step 5 – The Consumer Obtains an Access Token.
  Step 6 – The Consumer Accesses the Protected Resource.
```

4. **What is OpenID?:** OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords.

## Authorization and Authentication flows

1. **What is the difference between authorization and authentication?:** Authentication verifies the identity of a user or service, and authorization determines their access rights.

2. **What is Authorization Code Flow?:**  Enables a client application to obtain authorized access to protected resources like web APIs. The auth code flow requires a user-agent that supports redirection from the authorization server (the Microsoft identity platform) back to your application.

3. **What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?:** OpenId Connect flow specifically designed to authenticate native or mobile application users.

4. **What is Implicit Flow with Form Post?:** Uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

5. **What is Client Credentials Flow?:** Permissions are granted directly to the application itself by an administrator. When the app presents a token to a resource, the resource enforces that the app itself has authorization to perform an action since there is no user involved in the authentication.

6. **What is Device Authorization Flow?:** Contains two different paths; one occurs on the device requesting authorization and the other occurs in a browser.

7. **What is Resource Owner Password Flow?:** Resource Owner Password (ROP) Flow involves the application handling the user's password, it must not be used by third-party clients.