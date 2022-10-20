# Neural_Network_Charity_Analysis
Deep ML

## Overview of the analysis

To use machine learning and neural networks with the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup and to help the foundation predict where to make investments 


## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing

What variable(s) are considered the target(s) for your model?
    
    IS_SUCCESSFUL is considered the target for this model

What variable(s) are considered to be the features for your model?
    
    Everything are considered to be the features, except IS_SUCCESSFUL.

What variable(s) are neither targets nor features, and should be removed from the input data?
    
    EIN and NAME

### Compiling, Training, and Evaluating the Model


How many neurons, layers, and activation functions did you select for your neural network model, and why?
    There are two layers; the first layer;hidden_nodes_layer1 = 80, the second layerhidden_nodes_layer2 = 30 with relu for activation funtions.

Were you able to achieve the target model performance?
    The accuracy for this model is 72.45%.

What steps did you take to try and increase model performance?
   Additional the third layer;hidden_nodes_layer3 = 10. Use Sigmoid  activation funtions for the second and third layers. The model accuracy is increasing to 78.86%.


## Summary: 
There are 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

