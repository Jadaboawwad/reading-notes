## 1. Status Codes Based On REST Methods

        in this part we will discuss the following points

* In your own words, describe what each group of status code represents:
100’s = 
200’s =
300’s =
400’s =
500’s =
* What is a status code 202? 
* What is a status code 308?
* What code would you use if an update didn’t return data to a client?
* What code would you use if a resource used to exist but no longer does?
* What is the ‘Forbidden’ status code?

<br/>

                           The beginning of Part One

### 1.1: In your own words, describe what each group of status code represents:

100’s =These are informational status codes; 
200’s =These are the success codes. 
300’s =These are redirection codes.
400’s =These are the client error codes
500’s =These are the server error codes. 

### 1.2:  What is a status code 202?

this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

### 1.3:  What is a status code 308?

Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore.

### 1.4: What code would you use if an update didn’t return data to a client?

204 No Content

### 1.5: What code would you use if a resource used to exist but no longer does?

410 Gone

### 1.6: What is the ‘Forbidden’ status code?

The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
<br/>

    
                               The End of Part One

## 2. Build A REST API With Node.js, Express, & MongoDB - Quick 

        in this part we will discuss the following points

* Why do we need to pull our MongoDB database string out of our server and put it into our .env?
* What is middleware?
* What does app.use(express.json()) do?
* What does the /:id mean in a route?
* What is the difference beween PUT and PATCH?
* How do you make a defalut value in a schema?
* What does a 500 error status code mean?
* What is the difference between a status 200 and a status 201?

<br/>

                           The beginning of Part Tow

### 2.1: Why do we need to pull our MongoDB database string out of our server and put it into our .env?

When we deploy the server we are going to use anathor URL

### 2.2: What is middleware?

code that run when server gets the request but before it gets passed to the routes.

### 2.3: What does app.use(express.json()) do?

 accept JSON inside a get or post elements

### 2.4: What does the /:id mean in a route?

it's for getting on element in database this is a parameter and give access to whatever they pass after the first slash

### 2.5: What is the difference beween PUT and PATCH?

patch if we want to update based on what  the user passes
put it will update all information to describe it at once

### 2.6: How do you make a defalut value in a schema?

It will set a value by deffult for the key .

### 2.7: What does a 500 error status code mean?

there is an error on server cuse the actuall transaction not to work and the clinet has nothing to do

### 2.8: What is the difference between a status 200 and a status 201?

201 successfuly created an object 
200 everything was successful

<br/>

    
                               The End of Part Tow

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
