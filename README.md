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
In the first model 75, 25 Neurons were used to perfrom the model. In the second model 125,75, 25 neurons were used. In the third and final model 175, 125, 75, 25 neurons were used.
4 hidden layers were used to perfrom the final model.
Activation functions I used were simoid, relu, 
* Were you able to achieve the target model performance?
No I was not; I ran the model three times, each time increasing epochs and hidden layers. The closest I was able to perform was 73% accuracy I was unable to reach the 75% accuracy rating.

## Summary 
If I were to redo the model I would change my action functions to see if that would increase accuracy. Adding layers and neurons did increase accuracy but not to the 75% mark I was looking for. 


![initial-model](https://user-images.githubusercontent.com/93004710/166486952-10648b4a-e80a-4d1d-8c4a-e2f980c133f9.png)
![initial-model-scores](https://user-images.githubusercontent.com/93004710/166486972-264859bb-7f98-4cdb-8686-aba94becbde7.png)





![second-model](https://user-images.githubusercontent.com/93004710/166487003-21ad9ae6-6440-4c67-b6a3-ae7ab271a8c6.png)
![second-model-score](https://user-images.githubusercontent.com/93004710/166487034-7d58f065-8284-4b59-84bb-6b08b3e5a52a.png)





![final-model](https://user-images.githubusercontent.com/93004710/166487068-b0cb8c02-793f-4641-bca6-44d6d9bf2647.png)
![final-model-scores](https://user-images.githubusercontent.com/93004710/166487090-6d55b747-e19b-42ca-b3e8-70a38f8bc557.png)





