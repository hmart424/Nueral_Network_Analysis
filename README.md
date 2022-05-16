# Nueral_Network_Analysis

## Overview of the analysis

In todays Analyis we are going to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. We are using a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup. Today we will preprocess the data, compile, train, and evaluate the model, and finally optimnize the model. 

### Data Preprocessing

* What variable(s) are considered the target(s) for your model? The target variable is - IS_SUCCESSFUL column.

* What variable(s) are considered to be the features for your model? The features are every column except the IS_SUCCESSFUL column

* What variable(s) are neither targets nor features, and should be removed from the input data? 'EIN' & 'NAME'

### Compiling, Training, and Evaluating the model

* How many neurons, layers, and activation functions did you select for your neural network model, and why? In todays model i used two hidden layers and an input. The first hidden layer has 80 neurons, the second has 30. 

* Were you able to achieve the target model performance? I was only able to hit 72% after 3 tries.

* What steps did you take to try and increase model performance? We increased the number of neurons on one of the hidden layers, then we used a model with three hidden layers.

### Summary 

Although we did not achieve the target score of 75% accuracy. WE can use a models like the Random Forest Classifier to combine decision trees to generate a classified output and evaluate its performance against our deep learning model. Also the biggest factor which can always help in data science is more data.

