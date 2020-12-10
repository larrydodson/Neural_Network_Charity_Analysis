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

 Answer: Numerous attempts to increase the model's accuracy were made, none though that made any improvement. These included modifying: Hidden layers, number of neurons, pattern of neurons, activation functions for both hidden layers and for the output layer, optimizer and for number of epochs. Please see the table below in Deliverabl-3 for information of five of these attempts. 

.

### Deliverable 3: Optimize the Model


- Noisy variables: Additional preprocessing was used to attempt to remove noisy or less significant features from the model. None of the attempts made a significant difference in the end results for Model Accuracy. 


| Attempt # | Accuracy | Hidden Layers | Hidden Layers Neurons |  Hidden Layers Activation | Output Activation | Optimizer | Epochs |
| :---: | ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | 0.7255 | 2 | 90, 30 | relu | sigmoid | Adam | 50 |
| 2 | 0.7209 | 4 | 220, 120, 60, 60 | relu, tanh | sigmoid | Adam | 300 |
| 3 | 0.7224 | 3 | 60, 40, 20 | tanh | sigmoid | Adam | 50 |
| 4 | 0.7240 | 6 | 60, 120, 240, 240, 120, 60 | relu | sigmoid | Adam | 50 |
| 5 | 0.7226 | 3 | 6, 4, 6 | relu, tanh | sigmoid | Adam | 50 |



.

### Deliverable 4: Written Report 
   (this readme.md file)


.

<br>

---

## Summary
  (written summary)

### Recommendation 

#### Using a different model to solve the classification problem:


#### Explanation and Justification description:

.

.end

