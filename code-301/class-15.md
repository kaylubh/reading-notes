# Authentication

## What is OAuth

1. **What is OAuth?**

    OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

    > Explanation from [CSO Online](https://www.csoonline.com/article/562635/what-is-oauth-how-the-open-authorization-framework-works.html)

2. **Give an example of what using OAuth would look like.**

    The simplest example example of using OAuth is being able to sign in to a website using a login information you already have for another site.

3. **How does OAuth work? What are the steps that it takes to authenticate the user?**

    OAuth works by allowing a user to sign in to a website or service by using authorization from another service they are signed into. It authenticates the user by requesting the service they are already logged into provide the user a token which is then provide back to allow for authorization.

4. **What is OpenID?**

    OpenID provides a way for user to log in to services and works well with OAuth to provide authentication of the user whereas OAuth handles the authorization.

## Authorization and Authentication flows

1. **What is the difference between authorization and authentication?**

    Authentication is verifying the identify of the user while authorization is the verification of what the user has access to.

2. **What is Authorization Code Flow?**

    Authorization Code Flow is the exchanging of a code for a token.

3. **What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**

    The Authorization Code Flow with Proof Key for Code Exchange (PKCE) is similar to the Authorization Code Flow but addresses the security vulnerabilities of native apps and single-page apps by a secret on an authorization server called the code verifier. When a user requests authorization is generates a code challenge that must be verified by the code verifier in order to get an authorization code.

4. **What is Implicit Flow with Form Post?**

    Implicit Flow with Form Post is an alternative method of authorization for applications that are unable to store client secrets.

5. **What is Client Credentials Flow?**

    Client Credentials Flow is an authorization system for machine to machine (M2M) authorization versus user authorization.

6. **What is Device Authorization Flow?**

    Device Authorization Flow allows for authorization on devices with limited input options for the user. It navigates the user to link to be accessed on a better suited device like their computer or phone to finis the authorization process.

7. **What is Resource Owner Password Flow?**

    Resource Owner Password Flow authorizes the user using credentials such as a username and password managed by the application.

## Things I want to know more about

- How to use OAuth and more details about what all this means?

## References

- [CSO: What is OAuth? How the open authorization framework works](https://www.csoonline.com/article/562635/what-is-oauth-how-the-open-authorization-framework-works.html)
- [Auth0 Docs: Authentication and Authorization Flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)
