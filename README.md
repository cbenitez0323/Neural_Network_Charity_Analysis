# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of this analysis is to create a deep neural network to be able to categorize the success of the charities that AlphabetSoup contributed to. 

## Results: 
- Data Preprocessing
  - The variable 'IS_SUCCESSFUL' is the target because then model it to take the information about the charities and determine if the were succesful(1) or not(0)
  - The features used are application type, classification, use_case, organization, status, income AMT, special considerations and ask AMT.
  - The type o

- Compiling, Training, and Evaluating the Model
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - Was not able to increase model accuracy to over 75%
  - Steps to improve the model included increasing the number of nodes of the hidden layers, adding a hidden layer, changing the activation of the hidden layers and        removing features that may not be used to predict acurately. It should be noted, that the ask column which is the amount that was requested by the organization, had a huge range. The majority of the ask were $5000 but there was a huge range of varying asks as high as a billion in asking. Assuming this is the amount received, then this could impact the success of the project. Therefore an attempt was made to better normalize this data. However it may be better to scale or seperate the data.  

## Summary: 
The overall results show that the model is about 68% accurate. It was difficult to find way to improve the model without having the visual aspect of the data. If it could have been visualized then there would be an easier way to determine a better activation function to use. This could result in an optimized model. Also, the data needed to include more information about the moenetary aspect of the funding provided. The type of organization and the type of project the funding was put towards doesnt seem like it can be used to determind how successul the project would be. Receive a large sum of money versus $5000 for a similar type of project would confuse a model because it seems like the amount of money received holds more importance over the type of project it was put towards. 
