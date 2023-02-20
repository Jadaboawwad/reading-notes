## 1. List Comprehensions in Python

        in this part we will discuss the following points

* What is the syntax of List Comprehensions in Python
* How we create a list with range in python
* How to show the first letter of each word using Python?
* How toLower/Upper case converter using Python?

<br/>

                           The beginning of Part One

### 1.1: What is the syntax of List Comprehensions in Python?

```python

my_new_list = [ expression for item in list ]

```

### 1.2: How we create a list with range in python ?

```python

# [ expression for item in list ]
digits = [x for x in range(10)]

```

### 1.3 : How to show the first letter of each word using Python?

```python
authors = ["Ernest Hemingway","Langston Hughes","Frank Herbert","Toni Morrison",
    "Emily Dickson","Stephen King"]

letters = [ name[0] for name in authors ]
```

### 1.4 : How toLower/Upper case converter using Python?

```python
lower_case = [ letter.lower() for letter in ['A','B','C'] ]
upper_case = [ letter.upper() for letter in ['a','b','c'] ]
```

<br/>

    
                               The End of Part One

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
