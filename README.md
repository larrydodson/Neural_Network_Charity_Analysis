# Neural_Network_Charity_Analysis
Neural Network Modeling, UTMCC DataViz Module 19

---

## Contents 
  * Overview
    - Purpose
    - Resources
  * Results
  * Summary
 

---  

## Overview 
  
  In support of the Alphabet Soup Charity Foundation in order to predict where to make the most favorable investments, a multiple-layered deep learning neural network is created and tested. 

   ### Purpose
   To apply machine learning and neural networks, and using the features within the provided dataset, create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup Charity Foundation. 
  
   The deliverables are: 
   - Deliverable 1: Preprocessing Data for a Neural Network Model
   - Deliverable 2: Compile, Train, and Evaluate the Model
   - Deliverable 3: Optimize the Model
   - Deliverable 4: Written Report 
  
   
  
   ### Resources
  * Data source file: charity_data.csv
  * Software tools: Windows10, Jupyter Notebook, Python 3.8.3, Pandas, Scikit-learn, TensorFlow
  
<br>

--- 

## Results


### Deliverable 1: Preprocessing Data for a Neural Network Model



Questions on Data Preprocessing:

- *What variable(s) are considered the target(s) for your model?*  - Answer: **`IS_SUCCESSFUL`**

- *What variable(s) are considered to be the features for your model?*

 Answer: **`APPLICATION_TYPE,	AFFILIATION,	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS,	ASK_AM`**


- *What variable(s) are neither targets nor features, and should be removed from the input data?*  - Answer: **`EIN,	NAME`**

.

### Deliverable 2: Compile, Train, and Evaluate the Model



Questions on Compiling, Training, and Evaluating the Model:
- *How many neurons, layers, and activation functions did you select for your neural network model, and why?*

 Answer: For the initial model, the number of layers, neurons, activation functions and eopchs are shown in the table below. The number of layers and neurons were chosen based on a stated general guideline *a basic neural network is to have two to three times the amount of neurons in the hidden layer as the number of inputs* . The activation functions, the optimizer and epochs were chosen based on guidelines from the coursework, and from examples given in the challenge file. Other activation functions and epochs were used to attempt a higher accuracy for the model, and all of these are not shown in the jupyter notebook file, but these attempts did not improve the accuracy results. 


| Original<br>Model | Accuracy | Hidden Layers | Hidden Layers Neurons |  Hidden Layers Activation | Output Activation | Optimizer | Epochs |
| :---: | ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| - | 0.7263 | 2 | 80, 30 | relu | sigmoid | Adam | 50 |


- *Were you able to achieve the target model performance?*  - Answer: No


- *What steps did you take to try and increase model performance?*

 Answer: Numerous attempts to increase the model's accuracy were made, none though that made any improvement. These included modifying: Hidden layers, number of neurons, pattern of neurons, activation functions for both hidden layers and for the output layer, optimizer and for number of epochs. Please see the table below in Deliverable-3 for information of five of these attempts. 

.

### Deliverable 3: Optimize the Model


- Noisy variables: Additional preprocessing was used to attempt to remove noisy or less significant features from the model. None of the attempts made a significant difference in the end results for Model Accuracy. 


| Attempt # | Accuracy<br>% | Hidden Layers | Hidden Layers Neurons |  Hidden Layers Activation | Output Activation | Optimizer | Epochs |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | 72.55 | 2 | 90, 30 | relu | sigmoid | Adam | 50 |
| 2 | 72.09 | 4 | 220, 120, 60, 60 | relu, tanh | sigmoid | Adam | 300 |
| 3 | 72.24 | 3 | 60, 40, 20 | tanh | sigmoid | Adam | 50 |
| 4 | 72.53 | 6 | 60, 120, 240, 240, 120, 60 | relu | sigmoid | Adam | 400 |
| 5 | 72.56 | 3 | 40, 20, 20 | sigmoid, relu | sigmoid | Adam | 100 |

.

### Deliverable 4: Written Report 
   (this readme.md file)

.

---

## Summary

   In this project a deep learning neural network model was created, trained, and defined using an available data set on charitable donations to various entities. The goal was to create a model to predict the success of candidate companies receiving donations, using data of known success. Included within this project goal was to estimate the ability of the model itself with regard to the accuracy of prediction, with an accuracy score goal target of greater than 75%. 
   
   In order to attempt to improve the model accuracy, the model parameters were modified by changing available settings after training for parameters that included number of hidden layers, nodes or neurons in each hidden layer, the activation function for each hidden layer and for the output layer, the loss function, the optimizer function, and the number of epochs. Also, the base dataset was modified to remove noisy outliers and to drop other features that would not likely be significant to the results. 
   The overall the accuracy scores changed little from each attempt, with results from 72.1 to 72.6%. 

#### Using a model to solve the classification problem, and justification:

   For solution to solve a classification problem, the recommendation is to use the sigmoid activation function. With reference to the literature and documentation, the resulting sigmoid activation function values are normalized to a probability between 0 and 1, which is ideal for binary classification.  The defined output of this project's model was for a binary classification, for **`IS_SUCCESSFUL`** as 1 or 0. Therefore, the sigmoid function was used for each attempt. 

.

.end

