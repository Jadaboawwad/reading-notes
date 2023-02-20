## 1.  Putting it all together:
        in this part we will discuss the following points


* How would you break a mock into a component heirarchy?
* What is the single responsibility principle and how does it apply to components?
* What does it mean to build a ‘static’ version of your application?
* Once you have a static application, what do you need to add?
* What are the three questions you can ask to determine if something is state?
* How can you identify where state needs to live?

<br/>

                           The beginning of Part One

### 1.1: How would you break a mock into a component heirarchy?
But how do you know what should be its own component? Use the same techniques for deciding if you should create a new function or object. One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.



### 1.2:What is the single responsibility principle and how does it apply to components?
that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.


### 1.3: What does it mean to build a ‘static’ version of your application?

The easiest way is to build a version that takes your data model and renders the UI but has no interactivity. 

### 1.4 :Once you have a static application, what do you need to add?
add the instances ..


### 1.5 : What are the three questions you can ask to determine if something is state?
the data will be inside the component of from outside?
the data is static or daynamic?
what is the data flow direction ?
### 1.6 : How can you identify where state needs to live?

- Identify every component that renders something based on that state.

- Find a common owner component (a single component above all the components that need the state in the hierarchy).

- Either the common owner or another component higher up in the hierarchy should own the state.

- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.




<br/>

    
                               The End of Part One

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
