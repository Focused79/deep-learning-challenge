# Module 21 Report

## Overview of the Analysis

* The goal in constructing a deep learning neural network was to aid Alphabet Soup with a tool (model) to make predictions on the company's successful funding ventures. Alphabet Soup provided 34000 organizations who received funding from the company over several years. The metadata from these organizations provided a number of features (independent variables) to which an outcome was discerned. The outcome (or dependent variable), "IS-SUCCESSFUL", was the binary indicator of success or failure of funding the venture.  The dataset's features were optimized to create a binary classifier that could predict whether applicants will be successful if funded by Alphabet Soup. Much of the data underwent preprocessing improvements, such as cutting off rare categorical variables into an "other" catch-all bucket. In addition, pd.get_dummies was used to encode categorical variables. Finally, the training and testing features were scaled. The neural network model was trained and tested for the accuracy of its predictions.  

## Results 

The neural network model accurately made predictions 73-74% of the time after tweaking hyperparameters, such as activations functions, number of epochs, and network architecture, i.e. number of input layers, hidden layers. The researcher dabbled in using different optimizers with little success. A second neural network was created with the kerastuner library. The loop created the ideal hyperparameters. The result was only marginally better, though still falling short of 75% accuracy. 


Overall, the predictive ability of the models was moderately successful.

## Resources used in module:
1. Class lectures/slides.
2. Class activities. 
