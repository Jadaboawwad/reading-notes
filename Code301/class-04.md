## 1.  React Docs - Forms:
        in this part we will discuss the following points


* What is a ‘Controlled Component’?

* Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

* How do we target what the user is entering if we have an event handler on an input field?


<br/>

                           The beginning of Part One

### 1.1: What is a ‘Controlled Component’?

In HTML, form elements such as input, textarea, and select typically maintain their own state and update it based on user input. 

In React, mutable state is typically kept in the state property of components, and only updated with setState().

We can combine the two by making the React state be the “single source of truth”.       

Then the React component that renders a form also controls what happens in that form on subsequent user input. 
### 1.2: Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

onChange={this.handleChange}
is the Magic sentance for every string written the handelChange will invoked and changig the state by SetState function


### 1.3: How do we target what the user is entering if we have an event handler on an input field?

you can now pass the value to other UI elements too, or reset it from other event handlers.




<br/>

    
                               The End of Part One


## 2. The Conditional (Ternary) Operator Explained
        in this part we will discuss the following points


* Why would we use a ternary operator?
* Rewrite the following statement using a ternary statement:

<br/>

                           The beginning of Part Tow

### 2.1: Why would we use a ternary operator?  

1. The condition is what you’re actually testing. The result of your condition should be true or false or at least coerce to either boolean value.
2. ! ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.

3. Finally a : colon. If your condition evaluates to false, any code after the colon is executed.

### 2.2: Rewrite the following statement using a ternary statement:

```javascript
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```
- ## Solution
```javascript
x===y ? console.log(true) : console.log(false)
```
<br/>

    
                               The End of Part Tow

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
