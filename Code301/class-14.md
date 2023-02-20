## 1. What is OAuth

        in this part we will discuss the following points

* What is OAuth?
* Give an example of what using OAuth would look like.
* How does OAuth work? What are the steps that it * takes to authenticate the user?
* What is OpenID?

<br/>

                           The beginning of Part One

### 1.1: What is OAuth?

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

### 1.2: Give an example of what using OAuth would look like.

The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.

### 1.3: How does OAuth work? What are the steps that it takes to authenticate the user?

The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
The first site gives this token and secret to the initiating user’s client software.
The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
The user approves (or their software silently approves) a particular transaction type at the first website.
The user is given an approved access token (notice it’s no longer a request token).
The user gives the approved access token to the first website.
The first website gives the access token to the second website as proof of authentication on behalf of the user.
The second website lets the first website access their site on behalf of the user.
The user sees a successfully completed transaction occurring.
OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

### 1.4: What is OpenID?

OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."
<br/>

    
                               The End of Part One

## 2. Authorization and Authentication flows

        in this part we will discuss the following points

*
* What is the difference between authorization and * authentication?
* What is Authorization Code Flow?
* What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
* What is Implicit Flow with Form Post?
* What is Client Credentials Flow?
* What is Device Authorization Flow?
* What is Resource Owner Password Flow?

<br/>

                           The beginning of Part Tow

### 2.1: What is the difference between authorization and authentication?

In simple terms, authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.

Comparing these processes to a real-world example, when you go through security in an airport, you show your ID to authenticate your identity. Then, when you arrive at the gate, you present your boarding pass to the flight attendant, so they can authorize you to board your flight and allow access to the plane.

### 2.2: What is Authorization Code Flow?

 the source code is not publicly exposed, they can use the Authorization Code Flow which exchanges an Authorization Code for a token. Your app must be server-side because during this exchange, you must also pass along your application's Client Secret, which must always be kept secure, and you will have to store it in your client.

### 2.3: What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The PKCE-enhanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; 

### 2.4: What is Implicit Flow with Form Post?

Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, you don’t need to obtain, maintain, use, and protect a secret in your application.

### 2.5: What is Client Credentials Flow?

With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense.

### 2.6: What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text. 

### 2.7: What is Resource Owner Password Flow?

Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow , which requests that users provide credentials (username and password), typically using an interactive form. Because credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token, it is imperative that the application is absolutely trusted with this informati
<br/>

    
                               The End of Part Tow

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
