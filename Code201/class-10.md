## 1.Error Handling & Debugging

        in this part we will discuss the following points

- What are code three living area of Execution Context. 
- What are tow types of variable scopes.
- How we can imagine the scope.
- What are three console methods.
- Give a summary for debugging proces.
<br/>

                           The beginning of Part One 

### 1.1 : The code three living area of Execution Context are:


- **GLOBAL CONTEXT** :Code that is in the script, but not in a function.
There is only one global context in any page
- **FUNCTION CONTEXT** Code that is being run within a function. Each function has its own function context.
- **EVAL CONTEXT** : Text is executed like code in an internal func tion

### 1.2 : The tow types of variable scopes are

- **GLOBAL SCOPE** :
    - If a variable is declared outside a function, it can
    be used anywhere because it has global scope.
    - If you do not use the var keyword when creating
a variable, it is placed in global scope.
- **FUNCTION-LEVEL SCOPE** :
    - When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope


### 1.3 : We can imagine the scope as the following:

- Imagine that each function is a nesting doll. The children can ask the parents for information in their variables. But the parents cannot get variables from their children. Each child will get the sameanswer from the same parent.

### 1.4 : The console methods are:

- console. info() can be used for general information
n
- console.warn() can be used for warnings
- console.error() can be used to hold errors
- console.group() If you want to write a set of related data to the console

### 1.5 : a Summary for debugging process.

- Debugging is the process of finding errors. It involves a
process of deduction.

- The console helps narrow down the area in which the
error is located, so you can try to find the exact error.

- JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.

- If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.

<br/>
    
                               The End of Part One

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
