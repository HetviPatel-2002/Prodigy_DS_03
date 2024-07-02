# Building a Decision Tree Classifier

## Introduction

In this project, I built a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used for this project is the Bank Marketing dataset from the UCI Machine Learning Repository.

## Dataset

The dataset contains information about direct marketing campaigns of a Portuguese banking institution. The goal is to predict if the client will subscribe to a term deposit.

## Steps Involved

1. Data Loading
2. Data Preprocessing
3. Model Training
4. Model Evaluation

## Data Loading

First, let's load the dataset.

```python
import pandas as pd

# Load the dataset
url = "https://archive.ics.uci.edu/ml/machine-learning-databases/00222/bank-additional-full.csv"
data = pd.read_csv(url, sep=';')

# Display the first few rows of the dataset
data.head()
