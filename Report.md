# Report

## Overview of the analysis:
Alphabet Soup is a nonprofit foundation that is looking for our assistance in developing a binary classifier that can predict whether candidates who get funding from Alphabet Soup will succeed or not using machine learning and neural network variables in a dataset.

## Results:
### Data Preprocessing
* What variable(s) are the target(s) for your model?
    * The 'IS_SUCCESSFUL' column is the target
* What variable(s) are the features for your model?
    * By dropping the 'IS_SUCCESSFUL' column, every other colum are the features for the model
* What variable(s) should be removed from the input data because they are neither targets nor features?
    * The EIN' and 'NAME' columns were removed
### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * I selected 80 hidden notes for layer 1 and 30 hidden nodes for layer 2 because choosing a small number of neurons and an optimum number of layers would be the most efficient way to monitor the performance of the model. My choice for my activation fucktion was because I knew it would have controlled the performance of the model
* Were you able to achieve the target model performance?
    * I was not able to acheive the target model performance as I only got 73% as my model accuracy
* What steps did you take in your attempts to increase model performance?
    * To increase my model's performance to 75%, I did not drop the 'NAME' column as I combine together in a new value, added another layer and selected other activation funcstions.

## Summary:
One attempt was done to achieve a target predictive accuracy of 75%. The Decision Tree technique is another model that can be used to tackle this classification issue because it takes a supervised approach. Given that the input has already undergone pre-processing, the leaf nodes that represent the class label and attributes will be able to represent the boolean functions for the discrete attributes that we require once the model has been trained.