## 1. What is Jupyter Lab

        in this part we will discuss the following points

* What is Jupyter Lab
* What are the features of Jupyter Lab
<br/>

                           The beginning of Part One

### 1.1: What is Jupyter Lab

JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner. For a demonstration of JupyterLab and its features, you can view this video

* with features  of :  

### 1.2:  What are the features of Jupyter Lab

 * Code Consoles provide transient scratchpads for running code interactively, with full support for rich output.
* Kernel-backed documents enable code in any text file (Markdown, Python, R, LaTeX, etc.) to be run interactively in any Jupyter kernel.

<br/>

    
                               The End of Part One

## 2. Numpy Tutorial 

        in this part we will discuss the following points

* What is Numpy

* How to view the lists of lists for CSV data ?

* How we are Creating A NumPy Array?

<br/>

                           The beginning of Part Tow

### 2.1: What is Numpy

NumPy is a commonly used Python data analysis package. By using NumPy, you can speed up your workflow, and interface with other packages in the Python ecosystem, like scikit-learn, that use NumPy under the hood.

### 2.2: How to view the lists of lists for CSV data ?

if we have a csv file called 'winequality-red.csv'
* Import the csv library.
* Open the winequality-red.csv file.
* With the file open, create a new csv.reader object.
* Pass in the keyword argument delimiter="; " to make sure that the records are - * split up on the semicolon character instead of the default comma character.
* Call the list type to get all the rows from the file.
* Assign the result to wines.

```python
import csv
with open('winequality-red.csv', 'r') as f:
    wines = list(csv.reader(f, delimiter=';'))

print(wines[:3])
```

### 2.3: How we are Creating A NumPy Array?

* Import the numpy package.
* Pass the list of lists wines into the array function, which converts it into a NumPy array.
* Exclude the header row with list slicing.
* Specify the keyword argument dtype to make sure each element is converted to a float. We’ll dive more into what the dtype is later on.

```python
import csv
with open("winequality-red.csv", 'r') as f:
    wines = list(csv.reader(f, delimiter=";"))
import numpy as np
wines = np.array(wines[1:], dtype=np.float)

wines

```

<br/>

    
                               The End of Part Tow

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
