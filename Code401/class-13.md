## 1. How to Run Linear Regression in Python

        in this part we will discuss the following points

* What is Scikit-learn ?
* What are the method we use in scikit-learn class ?
* What is Regression  ?
* What is underfitting and overfitting ?

<br/>

                           The beginning of Part One

### 1.1: What is Scikit-learn ?

Scikit-learn is a powerful Python module for machine learning. It contains function for regression, classification, clustering, model selection and dimensionality reduction.

### 1.2 : What are the method we use in scikit-learn class ?

lm.fit() -> fits a linear model

lm.predict() -> Predict Y using the linear model with estimated coefficients

lm.score() -> Returns the coefficient of determination (R^2). A measure of how well

### 1.3 : What is Regression ?

It's a way to predect a continous value by find a function that maps some features or variables to others sufficiently well.

The dependent features are called the dependent variables, outputs, or responses.

The independent features are called the independent variables, inputs, or predictors.

Regression problems usually have one continuous and unbounded dependent variable. The inputs, however, can be continuous, discrete, or even categorical data such as gender, nationality, brand, and so on.

### 1.4 : What is underfitting and overfitting ?

Underfitting occurs when a model can’t accurately capture the dependencies among data, usually as a consequence of its own simplicity. It often yields a low 𝑅² with known data and bad generalization capabilities when applied with new data.

Overfitting happens when a model learns both dependencies among data and random fluctuations. In other words, a model learns the existing data too well. Complex models, which have many features or terms, are often prone to overfitting. When applied to known data, such models usually yield high 𝑅². However, they often don’t generalize well and have significantly lower 𝑅² when used with new data.
<br/>

    
                               The End of Part One

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
