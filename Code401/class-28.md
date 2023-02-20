## 1. Django CRUD and Forms

        in this part we will discuss the following points

* What is HTML forms ?
* What is the role of server ?
* How Django form handle a process?

<br/>

                           The beginning of Part One

### 1.1: What is HTML forms ?

An HTML Form is a group of one or more fields/widgets on a web page, which can be used to collect information from users for submission to a server.

Forms are also a relatively secure way of sharing data with the server, as they allow us to send data in POST requests with cross-site request forgery protection.

### 1.2: What is the role of server ?

The role of the server is first to render the initial form state — either containing blank fields or pre-populated with initial values. After the user presses the submit button, the server will receive the form data with values from the web browser and must validate the information. If the form contains invalid data, the server should display the form again, this time with user-entered data in "valid" fields and messages to describe the problem for the invalid fields. Once the server gets a request with all valid form data, it can perform an appropriate action (e.g. saving the data, returning the result of a search, uploading a file, etc.) and then notify the user.


### 1.3 : How Django form handle a process?
the view gets a request, performs any actions required including reading data from the models, then generates and returns an HTML page (from a template, into which we pass a context containing the data to be displayed). 
<br/>

    
                               The End of Part One

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)

`
