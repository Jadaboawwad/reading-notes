
# What is Operators?

**operators**: the part of code which link to operands and there are too many types of it as the following:

- Assignment operators
- Comparison operators
- Arithmetic operators
- Bitwise operators
- Logical operators
- String operators
- Conditional (ternary) operator
- Comma operator
- Unary operators
- Relational operators

[Learn more from here..](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

loops: part of code which control the flow control of program and can execute somthing for many itterations and it can be implemented as *for loop* or **while loop**
  
# The syntax of **for loop**
  ```JavaScript
    for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
  ```

  * Example: this example will print the santance Walking east on step until the counter (step) reach it limit in every itteration the counter increase by one and the body of for is executed , finally if the step becomes 5 or greater the for loop will skipped

  ```JavaScript
    for (let step = 0; step < 5; step++) {
    // Runs 5 times, with values of step 0 through 4.
    console.log('Walking east one step');
    }
  ```

# The syntax of **while loop**
  ```JavaScript
    while(condtion)
    {
    console.log('Walking east one step');
    } 
  
  ```
  * Example: the same example can be done but with some changes in syntax also **while** loop logical condtion can be used but we cant use it in for loop.
  ```JavaScript
    while (step < 5) {
    // Runs 5 times, with values of step 0 through 4.
    console.log('Walking east one step');
    step+=1
    }
  ```

  also there is a special kind of while loop which is do while loop which execute its body once before its check the condtion.
 
  ```JavaScript
    do
    statement
    while (condition);
    }
  ```

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
