## 1. Understanding the JavaScript Call Stack

        in this part we will discuss the following points

* What is a ‘call’?
* How many ‘calls’ can happen at once?
* What does LIFO mean?
* Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
* What causes a Stack Overflow?

<br/>

                           The beginning of Part One

### 1.1: What is a ‘call’?

call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

### 1.2: How many ‘calls’ can happen at once?

is done, one at a time, from top to bottom. It means the call stack is synchronous.

### 1.3: What does LIFO mean?

t, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

### 1.4: Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![Example](https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv)

### 1.5: What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

<br/>

    
                               The End of Part One

## 2. JavaScript error messages

        in this part we will discuss the following points

* What is a ‘refrence error’?
* What is a ‘syntax error’?
* What is a ‘range error’?
* What is a ‘tyep error’?
* What is a breakpoint?
* What does the word ‘debugger’ do in your code?

<br/>

                           The beginning of Part Tow

### 2.1: What is a ‘refrence error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

### 2.2: What is a ‘syntax error’?

his occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

### 2.3: What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

### 2.4: What is a ‘tyep error’?

Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

### 2.5: What is a breakpoint?

The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.

### 2.6: What does the word ‘debugger’ do in your code?

Will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values

<br/>

    
                               The End of Part Tow

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
