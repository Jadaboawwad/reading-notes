## 1. Read & Write Files in Python

        in this part we will discuss the following points

* What is File
* How to open file in Python

<br/>

                           The beginning of Part One

### 1.1: What is File

a file is a contiguous set of bytes used to store data. 

consist of 
* Header: metadata about the contents of the file (file name, size, type, and so on)
* Data: contents of the file as written by the creator or editor
* End of file (EOF): special character that indicates the end of the file
* What second positional argument mode ?

### 1.2: How to open file in Python

* as the following 

```python
file = open('dog_breeds.txt')
```

* as best practise

```python

reader = open('dog_breeds.txt')
try:
    # Further file processing goes here
finally:
    reader.close()
    
```

* or

```python
with open('dog_breeds.txt') as reader:
```

### 1.3: What second positional argument mode. 

This argument is a string that contains multiple characters to represent how you want to open the file.

* 'r'	Open for reading (default)
* 'w'	Open for writing, truncating (overwriting) the file first
* 'rb' or 'wb'	Open in binary mode (read/write using byte data)

<br/>

    
                               The End of Part One

## 2. Exceptions in Python

        in this part we will discuss the following points

* Exceptions versus Syntax Errors
* What are the ways of Raising an Exception
* Summerize what Exceptions in python is

<br/>

                           The beginning of Part Tow

### 2.1: Exceptions versus Syntax Errors

Syntax errors occur when the parser detects an incorrect statement.
exception error occurs whenever syntactically correct Python code results in an error. 

### 2.2: What are the ways of Raising an Exception

1- The AssertionError Exception
2- The try and except
3- Cleaning Up After Using finally

### 2.3: Summerize what Exceptions in python is

* raise allows you to throw an exception at any time.
assert enables you to verify if a certain condition is met and throw an exception if it isn’t.

* In the try clause, all statements are executed until an exception is encountered.

* except is used to catch and handle the exception(s) that are encountered in the try clause.
* else lets you code sections that should run only when no exceptions are encountered in the try clause.

* finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions.

<br/>

    
                               The End of Part Tow

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
