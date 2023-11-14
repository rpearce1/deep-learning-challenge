# deep-learning-challenge

## Overview of the Analysis

In this analysis, we used a data set of 34,299 organizations from Alphabet Soup, a nonprofit foundation, to create a neural network model for determining if an organization receiving funding is likely to succeed. The model features included the organization's application type, affiliation type, classification, use case of the funds, organization type, income amount, special considerations, and the requested funding amount. The target of the model was a binary classifier of whether or not the organization went on to be successful.

## Results

The data was preprocessed to remove unnecessary features and simplify categorical variables. All available data were included except the organization name and identification number. 9 application types and 60 classification types were lumped into respective "Other" categories to reduce the amount of categorical variable types. Then dummy variables were created, the data was divided into training and test sets, and StandardScaler was used to scale the data before input into the model.
  


## Summary

