# Advertising Logistic Regression Project

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Libraries used](#libraries-used)
* [Dataset used](#dataset-used)
* [Built on](#built-on)
* [Questions answered](#questions-answered)
* [Model Training and Testing Steps](#model-training-and-testing-steps)
* [Ackowledgements](#ackowledgements)
* [Author](#author)


## About the Project 
Exploratory Data Analysis of an advertising company's dataset to answer the problem statement given.</br></br>
The python notebook __"02-Logistic Regression Project"__ contains an initial EDA of data from the hypothetical company and analyzes how different features impact the probability of a customer clicking on the advertisement. 

It dives into how certain features impact each other and our target variable as well as looks at certain metrics in order to evaluate the model and see how well it is able to predict whether the user has clicked on the ad or not. 

## Libraries used 
* Numpy
* Pandas
* Matplotlib
* Seaborn
* sklearn

```bash
import numpy as np
import pandas as pd
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import classification_report,confusion_matrix
```

## Dataset used 
* __Perian Data__ - Advertising Dataset

## Built with
* Jupyter Notebook

## Questions answered 

1. What is the age distribution of customers using the advertising service?
2. How does the age of consumers correlate to the Area Income?
3. How does the age of the customer correlate to the time they spend on the App daily?
4. How is the Area Income of a user correlated to the daily usage of internet?

## Model Training and Testing Steps
1. Training the Model
2. Predicting the Test Data
3. Evaluating the Model

## Ackowledgements
* <a href='http://www.pieriandata.com'>Perian Data</a> - Dataset

## Author - Sharan Sukesh
