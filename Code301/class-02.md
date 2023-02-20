## 1. React lifecycle:

        in this part we will discuss the following points


* Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
* What is the very first thing to happen in the lifecycle of React?
* Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
* What does componentDidMount do?



<br/>

                           The beginning of Part One

### 1.1: Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?


When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

so the reneder happend before.


### 1.2:What is the very first thing to happen in the lifecycle of React?
Mounting static getDerivedStateFromProps

### 1.3:Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

1. constructor 
2. render
3. React Updates 
4. componentDidMount 
5. componentWillUnmount

### 1.4:What does componentDidMount do?

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.

<br/>

    
                               The End of Part One

## 2. React State Vs Props:

        in this part we will discuss the following points


* What types of things can you pass in the props?
* What is the big difference between props and state?
* When do we re-render our application?
* What are some examples of things that we could store in state?



<br/>

                           The beginning of Part Tow

### 2.1: What types of things can you pass in the props?
- Component that need to be inisialized
- Display Static Text like titles




### 2.2: What is the big difference between props and state?
- The props set outside the component but the state is set inside the componont.
- The props is static data but state is dynamic data

### 2.3: When do we re-render our application?
When we creat a component we pass the props for it

### 2.4: What are some examples of things that we could store in state?
- The form
- Dynamic Counter state


<br/>

    
                               The End of Part Tow


<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
