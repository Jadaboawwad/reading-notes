## 1. Bird's Eye View

                in this part we will discuss the following points

* What are five cores steps of Machine Learning ?
* Is Machine learning all about algortims ?
* What are the terminology of Machine learning ?

<br/>

                           The beginning of Part One

### 1.1 : What are five cores steps of Machine Learning and situational steps ?

* Cores:
1. exploratory analysis
2. data cleaning
3. feature engineering
4. algorithm selection 
5. model training

* Situational steps:
1. Project Scoping
2. Data Wrangling
3. Preprocessing
4. Ensembling

### 1.2 : Is Machine learning all about algortims ?

Machine learning is not about algorithms.
Machine learning is a comprehensive approach to solving problems...
Machine learning is the practice of teaching computers how to learn patterns from data, often for making decisions or predictions.
For true machine learning, the computer must be able to learn patterns that it's not explicitly programmed to identify.

### 1.3 : What are the terminology of Machine learning ?

* Model - a set of patterns learned from data.
* Algorithm - a specific ML process used to train a model.
* Training data - the dataset from which the algorithm learns the model.
* Test data - a new dataset for reliably evaluating model performance.
* Features - Variables (columns) in the dataset used to train the model.
* Target variable - A specific variable you're trying to predict.
* Observations - Data points (rows) in the dataset

<br/>

    
                               The End of Part One

## 2. Exploratory Analysis

        in this part we will discuss the following points

* Why explore your dataset ? 
* What are the questions I ask about Data?
* What is the next step after answering these questions ?

<br/>

                           The beginning of Part Tow

### 2.1: Why explore your dataset ? 

* Doing so upfront will make the rest of the project much smoother, in 3 main ways:

* You’ll gain valuable hints for Data Cleaning (which can make or break your models).
* You’ll think of ideas for Feature Engineering (which can take your models from good to great).
* You’ll get a "feel" for the dataset, which will help you communicate results and deliver greater impact.

### 2.1: What are the questions I ask about Data?

How many observations do I have?
How many features?
What are the data types of my features? Are they numeric? Categorical?
Do I have a target variable?

Do the columns make sense?
Do the values in those columns make sense?
Are the values on the right scale?
Is missing data going to be a big problem based on a quick eyeball test?\

### 2.2: What is the next step after answering these questions ?

1. Plot Numerical Distributions : 
   **Histogram**
* We look out for :
    - Distributions that are unexpected
    - Potential outliers that don't make sense
    - Features that should be binary (i.e. "wannabe indicator variables")
    - Boundaries that don't make sense
    - Potential measurement errors
1. Plot Categorical Distributions
2. **BarPlot**
* We look out for :
   - sparse classes :  which are classes that have a very small number of observations.

    In the best case, they don't influence the model much.
    In the worse case, they can cause the model to be overfit.

3. Plot Segmentations
    **BoxPlot**
    Segmentations are powerful ways to observe the relationship between categorical features and numeric features.

4. Study Correlation
   **HeatMap**
* correlations allow you to look at the relationships between numeric features and other numeric features.
   - Positive correlation means that as one feature increases, the other increases.
   - Negative correlation means that as one feature increases, the other decreases. 
   attended.

<br/>

    
                               The End of Part Tow

## 3. Data Cleaning

        in this part we will discuss the following points

* What Are things I want to clean in data ?
* What is Feature Engineering?
* What Are things I can do with Feature Engineering?

<br/>

                           The beginning of Part Three

### 3.1: What Are things I want to clean in data ?

1. Remove Unwanted observations : This includes duplicate or irrelevant observations.
2. Fix Structural Errors : Structural errors are those that arise during measurement, data transfer, or other types of "poor housekeeping."for instance, you can check for typos or inconsistent capitalization.
3. Filter Unwanted Outliers : In general, if you have a legitimate reason to remove an outlier, it will help your model’s performance.
However, outliers are innocent until proven guilty.\
4. Handle Missing Data: 
    by :

    - Dropping observations that have missing values
    - Imputing the missing values based on other observations

### 3.2: What is Feature Engineering?

Feature engineering is about creating new input features from your existing ones.
In general, you can think of data cleaning as a process of subtraction and feature engineering as a process of addition.\

* You can isolate and highlight key information, which helps your algorithms "focus" on what’s important.
* You can bring in your own domain expertise.
* Most importantly, once you understand the "vocabulary" of feature engineering, you can bring in other people’s domain expertise!

### 3.3 : What Are things I can do with Feature Engineering?

1. Create Interaction Features : can be products, sums, or differences between two features.
2. Combine Sparse Classes
3. Add Dummy Variables
4. Remove Unused Features
<br/>

    
                               The End of Part Three

## 4. Algorithm Selection

        in this part we will discuss the following points

* What is Regularization in Machine Learning?
* What are Regularized Regression Algos ?
* How About Decision Tree Algos ? 
* How about Random forests and boosted trees ?
* Finally ?
<br/>

                           The beginning of Part Four
               

### 4.1: What Regularization in Machine Learning?

Regularization is a technique used to prevent overfitting by artificially penalizing model coefficients.
Let's take an extreme example to illustrate why this happens:
Let's say you have 100 observations in your training dataset.
Let's say you also have 100 features.
If you fit a linear regression model with all of those 100 features, you can perfectly "memorize" the training set.
Each coefficient would simply memorize one observation. This model would have perfect accuracy on the training data, but perform poorly on unseen data.
It hasn’t learned the true underlying patterns; it has only memorized the noise in the training data.

### 4.2: What are Regularized Regression Algos ?

There are 3 common types of regularized linear regression algorithms.
1. Lasso Regression
2. Ridge Regression
3. Elastic-Net

### 4.2: How About Decision Tree Algos ? 

* It's prone to overfit with many input features.
* It cannot easily express non-linear relationships.

### 4.3: How about Random forests and boosted trees ?

* Random forests train a large number of "strong" decision trees and combine their predictions through bagging.
* Boosted trees train a sequence of "weak", constrained decision trees and combine their predictions through boosting

### 4.4 : Finally ?

Key takeaway: The most effective algorithms typically offer a combination of regularization, automatic feature selection, ability to express nonlinear relationships, and/or ensembling. Those algorithms include:

1. Lasso regression
2. Ridge regression
3. Elastic-Net
4. Random forest
5. Boosted tree

<br/>

    
                               The End of Part Four
                               

## 5. Model Training

        in this part we will discuss the following points

* What is Split Dataset ?
* What is Hyperparametr ?
* What is Cross Validation ?
* What is Fit and Tune ?

<br/>

                           The beginning of Part Five

### 5.1 : What is Split Dataset ?

If you evaluate your model on the same data you used to train it, your model could be very overfit and you wouldn’t even know! A model should be judged on its ability to predict new, unseen data.

### 5.2 : What is Hyperparametr ?

When we talk of tuning models, we specifically mean tuning hyperparameters.
There are two types of parameters in machine learning algorithms.
The key distinction is that model parameters can be learned directly from the training data while hyperparameters cannot.

### 5.3 : What is Cross Validation ?

Cross-validation is a method for getting a reliable estimate of model performance using only your training data.

### 5.4 : What is Fit and Tune ?

Basically, all we need to do is perform the entire cross-validation loop detailed above on each set of hyperparameter values we'd like to try.
<br/>

    
                               The End of Part Five

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
