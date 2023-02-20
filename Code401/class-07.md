## 1. Python Scope

 

        in this part we will discuss the following points

* What is the scope ?
* What is the Name spaces ?
* How we Modifying the Behavior of a Python Scope?

<br/>

                           The beginning of Part One

### 1.1: What is the scope

the scope of a name defines the area of a program in which you can unambiguously access that name, such as variables, functions, objects, and so on. 

The letters in the acronym LEGB stand for Local, Enclosing, Global, and Built-in scopes.

Global scope: The names that you define in this scope are available to all your code.

Local scope: The names that you define in this scope are only available or visible to the code within the scope.

### 1.2: What is the Name spaces

Python scopes are implemented as dictionaries that map names to objects. These dictionaries are commonly called namespaces. 

Names at the top level of a module are stored in the module’s namespace. In other words, they’re stored in the module’s .__dict__ attribute. 
<br/>

### 1.3 : How we Modifying the Behavior of a Python Scope?

by word global the names that you list in a global statement will be mapped to the global or module scope in which you define them.
Example :

```python
counter = 0  # A global name
def update_counter():
    global counter  # Declare counter as global
    counter = counter + 1  # Successfully update the counter

```

by word nonlocal names can be accessed from inner functions, but not assigned or updated.

Example

```python
def func():
    var = 100  # A nonlocal variable
    def nested():
        nonlocal var  # Declare var as nonlocal
        var += 100

    nested()
    print(var)

func()
```

    
                               The End of Part One

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
