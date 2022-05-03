# Neural_Network_Charity_Analysis

## Overview of the analysis: 
Explain the purpose of this analysis.
Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively



## Results: 

### Data Preprocessing
* What variable(s) are considered the target(s) for your model?
IS_SUCCESSFUL—Was the money used effectively, was the target varibale for the model.
* What variable(s) are considered to be the features for your model?
EIN and NAME—Identification columns, APPLICATION_TYPE—Alphabet Soup application type, AFFILIATION—Affiliated sector of industry, CLASSIFICATION—Government organization classification, USE_CASE—Use case for funding, ORGANIZATION—Organization type, STATUS—Active status, INCOME_AMT—Income classification, SPECIAL_CONSIDERATIONS—Special consideration for application, ASK_AMT—Funding amount requested, were all features used in the model except two that were removed.
* What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and NAME—Identification columns were removed from the model.
### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
Neurons were used to perfrom the model.
3 or 4 hidden layers were used to perfrom the model.
Activation functions I used were
* Were you able to achieve the target model performance?
No I was not; I ran the model three times, each time increasing epochs and hidden layers. The closest I was able to perform was 73% accuracy I was unable to reach the 75% accuracy rating.

## Summary 
If I were to redo the model I would change my action functions to see if that would increase accuracy. Adding layers and neurons did increase accuracy but not to the 75% mark I was looking for. 
