## 1. Classes and Objects

        in this part we will discuss the following points

* What is classes
* How we Accessing Object Variables
* How we Accessing Object Functions

<br/>

                           The beginning of Part One

### 1.1: What is classes

Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects.

### 1.2: How we Accessing Object Variables

using dot notation on the instance

### 1.3: How we Accessing Object Functions

using dot notation on the instance

<br/>

    
                               The End of Part One

## 2. Thinking Recursively

        in this part we will discuss the following points

* Waht is recursive function
* Mention a factorial function implementation as recursive function exampl

<br/>

                           The beginning of Part Tow

### 2.1:

Recursion  is  a function calls itself repeatedly and factorial exampl is an example of it the base case is one and it return invoking itself by n*factorial(n-1)

### 2.2: Factorial Function Implementation

```python
def recur_factorial(n):
if n == 1:
   return n
elif n < 1:
   return ("NA")
else:
   return n*recur_factorial(n-1)
```

<br/>

    
                               The End of Part Tow

## 3. Pytest Fixtures and Coverage

        in this part we will discuss the following points

* Why we use Fixtures in python
* How we use Fixtures in python

<br/>

                           The beginning of Part Three

<br/>

### 1.1: Why we use Fixtures in python

When you're writing tests, you're rarely going to write just one or two. Rather, you're going to write an entire "test suite", with each test aiming to check a different path through your code. In many cases, this means you'll have a few tests with similar characteristics, something that pytest handles with "parametrized tests".

### 1.2: How we use Fixtures in python

```python
@pytest.fixture
def simple_file():
   return StringIO('\n'.join(['abc', 'def', 'ghi', 'jkl']))

``

                               The End of Part Three

[BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
