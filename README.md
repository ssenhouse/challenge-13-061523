# *challenge-13-061523*
---
# Repository for Challenge 13 Fin Tech BootCamp
## Venture Funding with Deep Learning
---
![image for challenge 13](/Starter_Code/images/13-4-challenge-image.png)

## Overview of Analysis
The objective of this challenge was to create a model that would evaluate if the businesses that a venture capitalist firm (Alphabet Soup) will result in a successful business. To complete this task, I used machine learning and, specifically, neural network tools to analyze the data. 

To improve the accuracy of my model, I created two alternative models (A1 and A2) to increase the model's accuracy. 

The source data from this model was 34,000 different loans, which had 12 other columns with data on each of these loans. The problem required me to prepare the data for the model, fit the data to a model, and then test the model's output for accuracy. 

## Results
All three models run achieved an accuracy between 70 - 74% after running. The conditions for each model were as follows:

Original Model 

        * Used all columns from the data set
        * Used two hidden layers to model
        * Used 'relu' as the activation function and 'sigmoid' as the output function

![originalmodel](/Starter_Code/images/originalmodel.png)

Results show that the Accuracy = 72.85% and Loss = 55.26% 
        
Alternate Model 1

        * Used all of the columns from the data set
        * Used four hidden layers to model
        * Used 'relu' as the activation function and 'sigmoid' as the output function
        
![alternatemodel1](/Starter_Code/images/alternatemodel1.png)

Results show that accuracy = and Loss =

Alternate Model 2

        * Used some of the columns from the original dataframe. Eliminated(Classification, Application_Type, Status, Special Considerations)
        * Used two hidden layers to model
        * Used 'relu' as the activation function and 'sigmoid' as the output function 
     
![table showing unique values](/Starter_Code/images/tableofvaluesincolumns.png)

Note: I eliminated the columns because they had a lot of unique values or only two unique values similar to our output variable. 

## Summary
Results from these models are very similar in accuracy ranging from 70% - 73%. The Alternate Model 2 had the lowest accuracy at 70%. However, Alternate Model 2 had the least number of categorical variables, which may prove beneficial as it explains the predictable factors in a successful business.
