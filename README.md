# deep-learning-challenge

## Overview of the Analysis

In this analysis, we used a data set of 34,299 organizations from Alphabet Soup, a nonprofit foundation, to create a neural network model for determining if an organization receiving funding is likely to succeed. The model features included the organization's application type, affiliation type, classification, use case of the funds, organization type, income amount, special considerations, and the requested funding amount. The target of the model was a binary classifier of whether or not the organization went on to be successful. 

## Results
The data was preprocessed to remove unnecessary features and simplify categorical variables. All available data were included except the organization name and identification number. 9 application types and 60 classification types were lumped into respective "Other" categories to reduce the amount of categorical variable types. Then dummy variables were created, the data was divided into training and test sets, and StandardScaler was used to scale the data before input into the model. The initial model was created with 3 layers, an initial 80 node input layer, a 30 node second layer, both with relu activation functions, followed by a single node output layer with a sigmoid activation function. This scale was chosen to create a model that was not overly complex but still with the capacity to handle the 43 input parameters. 
After running the model for 100 epochs, the model yielded an accuracy of 0.74 on the training set with a loss of 0.54. Similarly, the test set was evaluated with an accuracy of 0.73 and a loss of 0.56. In attempting to optimize model performance, changes were made to the data preprocessing and model structure. 

  


## Summary

