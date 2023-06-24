# *challenge-13-061523*
---
# Repository for Challenge 13 Fin Tech BootCam
## Venture Funding with Deep Learning
---
![image for challenge 13](/Starter_Code/images/13-4-challenge-image.png)

## Overview of Analysis
The objective of this challenge was to use create a model that will evaluate if the businesses that a venture capitalist firm (Alphabet Soup) will result in a successful business. To complete this task, used machine learning and specifically neural network tools to analyze the data. 

In an attempt to improve the accuracy of my model, I created two alternatives models (A1 and A2) in an attempt to increase the accuracy of the model. 

The source data from this model was 34,000 different loans, which had 12 different columns with data on each of these loans. The problem required me to prepare the data for the model, fit the data to a model, and then test the output of the model for accuracy. 

## Results
All three models run achieved an accuracy between 70 - 74% after running. The conditions for each model were as follows:

Original Model 

        * Used all columns from the data set
        * Used 2 hidden layers to model
        * Used 'relu' as the activation function and 'sigmoid' as the output function

![originalmodel](/Starter_Code/images/originalmodel.png)

Results show that the Accuracy = 72.85% and Loss = 55.26% 
        
Alternate Model 1

        * Used all of the columns from the data set
        * Used 4 hidden layers to model
        * Used 'relu' as the activation function and 'sigmoid' as the output function
        
![alternatemodel1](/Starter_Code/images/alternatemodel1.png)

Results show that Accuracy = and Loss =

Alternate Model 2

        * Used some of the columns from the original dataframe. Eliminated(Classification, Application_Type, Status, Special Considerations)
        * Used 2 hidden layers to model
        * Used 'relu' as the activation function and 'sigmoid' as the output function
        
    Note: Columns were eliminated because these columns had either a lot of unique values, or they had only 2 unique values which is similar to our output variable. 
    ![table showing unique values](/Starter_Code/images/tableofvaluesincolumns.png)
    
## Summary
Results from these models are very similar in accuracy ranging from 70% - 73%. The Alternate Model 2 which has the least number of categorical variables, and the lowest accuracy at 70%. Howeve may prove to beneficial as it provides a simplier explanation as to what are the predictable factors in successful business.