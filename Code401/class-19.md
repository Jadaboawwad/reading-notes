## 1. Regular Regression

        in this part we will discuss the following points

* What is Regualr Regression ? 
* What is the package used for regix in Python ?

<br/>

                           The beginning of Part One

### 1.1: What is Regular Regression ?

Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not. If you've ever used search engines, search and replace tools of word processors and text editors

### 1.2 : What is the package used for regix in Python ?

a pacakage named re

In Python, regular expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of import:

```python
import re
```

<br/>

    
                               The End of Part One

## 2. shutil

        in this part we will discuss the following points

* What is shutil ?
* Why do we use shtil ?
* Example of use

<br/>

                           The beginning of Part Tow

### 2.1: What is shutil ?

The shutil module includes high-level file operations such as copying and archiving.

### 2.2 : Why do we use shtil ?

copyfile() copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.

## 2.3 : Example of use 

```python
import glob
import shutil

print('BEFORE:', glob.glob('shutil_copyfile.*'))

shutil.copyfile('shutil_copyfile.py', 'shutil_copyfile.py.copy')

print('AFTER:', glob.glob('shutil_copyfile.*'))
```

<br/>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)

`
