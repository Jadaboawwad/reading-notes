## 1.  lists and keys:
        in this part we will discuss the following points


* What does .map() return?
* If I want to loop through an array and display each value in JSX, how do I do that in React?
* 1.3: Each list item needs a unique
* What is the purpose of a key?

<br/>

                           The beginning of Part One

### 1.1: What does .map() return?
In React, transforming arrays into lists of elements is nearly identical.
### 1.2: If I want to loop through an array and display each value in JSX, how do I do that in React?

we loop through the array using the JavaScript map() function. We return a element for each item. Finally, we assign the resulting array of elements to listItems:

   as example we use :
                                
```javascript
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
```
### 1.3: Each list item needs a unique
When you run this code, you’ll be given a warning that a key should be provided for list items. A “key” is a special string attribute you need to include when creating lists of elements
### 1.4: What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed
<br/>

    
                               The End of Part One


## 2.The Spread Operator

        in this part we will discuss the following points


* What is the spread operator? 
* List 4 things that the spread operator can do.
* Give an example of using the spread operator to combine two arrays.
* Give an example of using the spread operator to combine two objects into one

<br/>

                           The beginning of Part Tow

### 2.1: What is the spread operator? 
Spread operator allows an iterable to expand in places where 0+ arguments are expected.

### 2.2: List 4 things that the spread operator can do.

### 2.3:Give an example of using the spread operator to combine two arrays.

### 2.4: Give an example of using the spread operator to add a new item to an array.

### 2.5: Give an example of using the spread operator to combine two objects into one
<br/>

    
                               The End of Part Tow

## 3.How to Pass Functions Between Components

        in this part we will discuss the following points


* 

<br/>

                           The beginning of Part Three

### 2.1: In the video, what is the first step that the developer does to pass functions between components? 

He buld the constructer with its states and super 
and he create a div with function looping over a state object then he built the function which will be pass to the component.
### 2.2: In your own words, what does the increment function do?
it's maping the state object and for every element he check if the function passed key value matches the keyvalue of the state object it will update the other key value in it with returning the element it'self and saving them in variable which will be set again for the state object as an update to it.
### 2.3:How can you pass a method from a parent component into a child component?
by passing it as a probes and we can call it anywhere in child component.
### 2.4: How does the child component invoke a method that was passed to it from a parent component?
 by using this.props.functionName

<br/>

    
                               The End of Part Three



<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
