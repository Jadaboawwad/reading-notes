## 1. Dunder Methods

        in this part we will discuss the following points

- What Are Dunder Methods?
- How we can use a dunder method ?
- Give 5 examples of dunder methods ?
<br/>

                             The beginning of Part One

### 1.1: What Are Dunder Methods?

In Python, special methods are a set of predefined methods you can use to enrich your classes.

### 1.2: How we can use a dunder method ?

If we have a class with some methods and we want to get a value when we call a len method on it, we can
define a **str** method inside the class so we can use it's on invocation len()

### 1.3: Give 5 examples of dunder methods ?

1.  **init** : To construct account objects
2.  **str**, **repr** : repr is The “official” string representation of an object and str is The “informal” or nicely printable string representation of an object.
3.  **len**, **getitem**, **reversed** : In the object instance we can get the len , make it itrative and can be reversed

<br/>

                               The End of Part One

## 2. Iterators

        in this part we will discuss the following points

- How do Python’s elegant loop constructs work behind the scenes?
- Give a Summary for Iterators in python ?

<br/>

                           The beginning of Part Tow

### 2.1: How do Python’s elegant loop constructs work behind the scenes?

We first initialize the cursor and prepare it for reading, and then we can fetch data into local variables as needed from it, one element at a time.

Because there’s never more than one element “in flight”, this approach is highly memory-efficient. Our Repeater class provides an infinite sequence of elements and we can iterate over it just fine. Emulating the same with a Python list would be impossible—there’s no way we could create a list with an infinite number of elements in the first place. This makes iterators a very powerful concept.

On more abstract terms, iterators provide a common interface that allows you to process every element of a container while being completely isolated from the container’s internal structure.

Whether you’re dealing with a list of elements, a dictionary, an infinite sequence like the one provided by our Repeater class, or another sequence type—all of that is just an implementation detail. Every single one of these objects can be traversed in the same way by the power of iterators.

And as you’ve seen, there’s nothing special about for-in loops in Python. If you peek behind the curtain, it all comes down to calling the right dunder methods at the right time.v

### 2.2 : Give a Summary for Iterators in python ?

- Iterators provide a sequence interface to Python objects that’s memory efficient and considered - Pythonic. Behold the beauty of the for-in loop!
- To support iteration an object needs to implement the iterator protocol by providing the **iter** and **next** dunder methods.
- Class-based iterators are only one way to write iterable objects in Python. Also consider generators and generator expressions.

<br/>

                               The End of Part Tow

## 3. Generators

        in this part we will discuss the following points

- Give a Summary for Generators in python

<br/>

                           The beginning of Part Three

### 3.1: Give a summery for Generators in python ?

- Generator functions are syntactic sugar for writing objects that support the iterator protocol. Generators abstract away much of the boilerplate code needed when writing class-based iterators.
- The yield statement allows you to temporarily suspend execution of a generator function and to pass back values from it.
- Generators start raising StopIteration exceptions after control flow leaves the generator function by any means other than a yield statement.

<br/>

                               The End of Part Three

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
