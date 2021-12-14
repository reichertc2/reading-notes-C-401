# Code 401 - Advanced Software Development - Python

## Class 13 - Linear Regressions

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### How to Run Linear Regression in Python ([Article](https://bigdata-madesimple.com/how-to-run-linear-regression-in-python-scikit-learn/))
- NOTE: Since this demo was published scikit-learn has been updated. The train_test_split function is now imported from sklearn.model_selection

There are a few ways to implement linear regression in code. Typically, per the article the needed SDKs are:
```
import numpy as np
import pandas as pd
import scipy.stats as stats
import matplotlip as plt
import sklearn
```
To convert untitled column names to feature names ```data.columns = data.feature_names```.

Linear regression is an object and there are multitude of functions available a few key ones are:
- ```lm.fit()``` fits a linear model
- ```lm.predict()``` predict Y using the linear model with estimated coefficients
- ```im.score()``` returns the coefficient of determination

It looks as though the built in linear regression tool can be very helpful in creating visual representation and integrated prediction of a desired data series.

In short linear regression is a statistical tool that helps predict a given value on a preprovided data series. It is deterministic on a explanatory variable to predict the response variable. It visually looks like a scatter plot with a line running at the predicted mean of the data set.

### Resources

Pytest Fixtures ([Article](https://docs.pytest.org/en/latest/explanation/fixtures.html))

### Additional Resources

Linear Regression in Python ([Article](https://realpython.com/linear-regression-in-python/))

Introduction to Simple Linear Regressions ([Video](https://www.youtube.com/watch?v=KsVBBJRb9TE))

### Bookmark/Skim

Train & Test Splits ([Article](https://towardsdatascience.com/train-test-split-and-cross-validation-in-python-80b61beca4b6))

What is Linear Regression ([Article](https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/what-is-linear-regression/))

### Things I want to know more about

* 

Go [Home](index.md)