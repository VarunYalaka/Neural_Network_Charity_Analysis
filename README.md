# Neural_Network_Charity_Analysis


## Overview of the analysis: 
Using a binary classifier predicting whether applicants will be successful if funded by Alphabet Soup. CSV contains more than 34,000 organizations that have received funding from Alphabet Soup over the years. Build a neural network to determine which applications are more likely successful. 


## Results: 
### Data Preprocessing

* What variable(s) are considered the target(s) for your model?

  IS_SUCCESSFUL

* What variable(s) are considered to be the features for your model?

  * Application Type
  * Affiliation
  * Use Case
  * Special Consideration
  * Ask Amount
  * Income Amount
  * Classification

* What variable(s) are neither targets nor features, and should be removed from the input data?

  “EIN” and “NAME”

  ![Screenshot 2023-01-29 at 11 55 47 PM](https://user-images.githubusercontent.com/44387918/215425039-c3faf4b9-7b40-446f-b8ce-e3e28e86354e.png)

## Compiling, Training, and Evaluating the Model

*  How many neurons, layers, and activation functions did you select for your neural network model, and why?

  80  and 30 neurons and 2 layers to avoid The risk of overfitting, where a model becomes too specialized to the training data and does not generalize well   to new data. 

* Were you able to achieve the target model performance?

  No, achieved 72 % accuracy. 

![Screenshot 2023-01-29 at 11 55 09 PM](https://user-images.githubusercontent.com/44387918/215424981-18d26c15-e748-40c7-bdc8-d7381272e445.png)

* What steps did you take to try and increase model performance?

  * Increased neurons (80, 60 and 40) and layers =3 
  * Removed un useful information columns. 
  
  ![Screenshot 2023-01-30 at 12 07 05 AM](https://user-images.githubusercontent.com/44387918/215425749-90c1faab-5255-44b8-adf2-29618ac920ee.png)

  
### Summary:  

Need to adjust neurons, layers and other functions to achieve the accuracy goal. With the above parameters unable to reach the goal accuracy. Further need to increase / decrease the prioritization of other parameters to achieve the goal.   
