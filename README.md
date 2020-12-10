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

- *What variable(s) are considered the target(s) for your model?*

 Answer: **`IS_SUCCESSFUL`**

- *What variable(s) are considered to be the features for your model?*

 Answer: **`APPLICATION_TYPE,	AFFILIATION,	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS,	ASK_AM`**


- *What variable(s) are neither targets nor features, and should be removed from the input data?*

 Answer: **`EIN,	NAME`**

.

### Deliverable 2: Compile, Train, and Evaluate the Model



Questions on Compiling, Training, and Evaluating the Model:
- *How many neurons, layers, and activation functions did you select for your neural network model, and why?*


- *Were you able to achieve the target model performance?*


- *What steps did you take to try and increase model performance?*



.

### Deliverable 3: Optimize the Model


- Noisy variables removed from features: and through trail-and-error, none were removed that made a significant difference in the end result. 


| Model Factor selections | Attempt-1<br>(original) | Attempt-2 | Attempt-3 | Attempt-4 |
| ---: | :--- | :--- | :--- | :--- | 
| Hidden Layers:<br>Hidden Layers Nodes/Neurons:<br>Activation Function of Hidden Layers:<br><br> <br>Activation Function of Output:<br>Optimizer:<br>Epochs: | a | b | c | d |
| Loss:<br>Accuracy: | 1 | 2 | 3 | 4 |

| Attempt # | Accuracy | Hidden Layers | Hidden Layers Neurons |  Hidden Layers Activation | Output Activation | Optimizer | Epochs |
| :---: | ---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | . | . | . | . | . | . | . |
| 2 | . | . | . | . | . | . | . |
| 3 | . | . | . | . | . | . | . |
| 4 | . | . | . | . | . | . | . |



 *A good rule of thumb for a basic neural network is to have two to three times the amount of neurons in the hidden layer as the number of inputs.*


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

