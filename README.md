# Neural_Network_Charity_Analysis
Deep ML

## Overview of the analysis

To use machine learning and neural networks with the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup and to help the foundation predict where to make investments 


## Results

### Data Preprocessing

![1](https://github.com/Poonsri14/Neural_Network_Charity_Analysis/blob/main/Resource/mergeDF1.png)


What variable(s) are considered the target(s) for your model?
    
    IS_SUCCESSFUL is considered the target for this model

What variable(s) are considered to be the features for your model?
    
    Everything are considered to be the features, except IS_SUCCESSFUL.

What variable(s) are neither targets nor features, and should be removed from the input data?
    
    EIN and NAME

### Compiling, Training, and Evaluating the Model


![2](https://github.com/Poonsri14/Neural_Network_Charity_Analysis/blob/main/Resource/accuracy1.png)


How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
    There are two layers; the first layer;hidden_nodes_layer1 = 80, the second layerhidden_nodes_layer2 = 30 with relu for activation functions.

Were you able to achieve the target model performance?
   
    The accuracy for this model is 72.45%.



![3](https://github.com/Poonsri14/Neural_Network_Charity_Analysis/blob/main/Resource/accuracy2.png)

What steps did you take to try and increase model performance?

   Additional the third layer;hidden_nodes_layer3 = 10. Use Sigmoid  activation funtions for the second and third layers. The model accuracy is increasing to 78.86%.


## Summary

The latest test that has additional third layer and is changed the activation function to Sigmoid is 78.86% accuracy for model performance which is efficiency to perform and solve this classification problem. No additional test needed.

