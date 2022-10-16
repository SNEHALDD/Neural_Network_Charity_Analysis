# Neural_Network_Charity_Analysis

## Overview of the loan prediction risk analysis 

A hypothetical nonprofit foundation, Alphabet Soup, needs help analyzing the impact of their donations and vetting potential recipients by predicting which organizations are worth donating to and which are too high risk. I designed a deep learning neural network that evaluates all types of input data and produces a clear decision making result using the Python TensorFlow library.

## Resources
Data Source: charity_data.csv
Software: Python, Jupyter Notebook, TensorFlow 2.3.1, Scikit-learn


## Results
### Data Preprocessing

- "IS_SUCCESSFUL" is considered the target array for this model.

- I have considered  CLASSIFICATION, APPLICATION_TYPE, ASK_AMT, ORGANIZATION, AFFILIATION variables to be the features.

- Following variables are neither targets nor features and should be removed from the input data, EIN, NAME, STATUS, and SPECIAL_CONSIDERATION
Following pictures all show all the results.

### Compiling, Training, and Evaluating the Model

- I have included 120 neurons for layer 1 with activation function "sigmoid", 50 neurons for layer 2 with activation function "relu", 18 neurons for layer 3 with activation function "relu". I considered sigmoid function for layer 1 instead rely because it gave better results than before.

- I was not able to achieve the accuracy of 75%. I could only get accuracy of 70%.

- I tried to increase model performance by dropping some more columns which were not necessary for the analysis, added more neurons to the hidden layers, also used different activation functions, created more bins, decreasing values in some bins, also increased number of epochs.

Following pictures will show all the results.


## Summary : 
- After dropping unnecessary columns, adding neurons and hidden layers, changing activation functions provided the accuracy unto 70% with loss of 1.24.

- Random Forest Classifier could have also given better results. There are less parameters in traditional method. We can also get better output with just 2 hidden layers. It can run efficiently on large datasets.


