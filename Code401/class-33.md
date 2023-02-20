## 1.  JSON Web Tokens

        in this part we will discuss the following points

* What is JSON Web Token?
* When should you use JSON Web Tokens?
* 
*
*
*
*

<br/>

                           The beginning of Part One

### 1.1: What is JSON Web Token?

JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
### 1.2: When should you use JSON Web Tokens?

Authorization: This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains.

Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header and the payload, you can also verify that the content hasn't been tampered with.

### 1.3: What is the JSON Web Token structure?

In its compact form, JSON Web Tokens consist of three parts separated by dots (.), which are:
- Header
- Payload
- Signature

<br/>

    
                               The End of Part One

## 2. DRF JWT Authentication

        in this part we will discuss the following points

* What is JWT ?


<br/>

                           The beginning of Part Tow

### 2.1: What is JWT ?
JWT stand for JSON Web Token and it is an authentication strategy used by client/server applications where the client is a Web application using JavaScript and some frontend framework like Angular, React or VueJS.

<br/>

    
                               The End of Part Tow

## 3. Django Runserver Is Not Your Production Server

        in this part we will discuss the following points

* How Does Django Fit In? 
<br/>

                           The beginning of Part Three

### 3.1: How Does Django Fit In ? 
Your Django app does not actually run as you would think a server would - waiting for requests and reacting to them. Your project provides a uwsgi.py file, which contains a function to be called by the application server. This function gets a Python object representing the incoming request.

This function calls your code, and produces a response object which is passed to the WSGI server. There the response is translated into a HTTP response and is passed back to the web server, which finally delivers it to the user.

<br/>

    
                               The End of Part Three

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
`