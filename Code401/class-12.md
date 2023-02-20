## 1. Pandas in 10

        in this part we will discuss the following points

* What kind of data does pandas handle?
* How do I select a subset of a DataFrame?¶
* How do I filter specific rows from a DataFrame?¶
* How to calculate summary statistics?¶

<br/>

                           The beginning of Part One

### 1.1:  What kind of data does pandas handle?

To load the pandas package and start working with it, import the package. The community agreed alias for pandas is pd, so loading pandas as pd is assumed standard practice for all of the pandas documentation.

Each column in a DataFrame is a Series

### 1.2: How do I select a subset of a DataFrame?¶

let suppose that ages is dataframe so by ages.head() you print a part of dataframe

### 1.3: How do I filter specific rows from a DataFrame?¶

let suppose that titanic is data frame so by above_35 = titanic[titanic["Age"] > 35]

### 1.4 : How to calculate summary statistics?¶

let suppose that titanic is data frame and age is a feature so by titanic["Age"].mean()

### 1.5 : How to reshape the layout of tables?

let suppose that titanic is data frame and age is a feature so by titanic.sort_values(by="Age").head()
<br/>

    

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
