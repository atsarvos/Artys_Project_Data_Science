# Artys-Project---Data-Science
The Repository will house the working files for my General Assembly Project

Initially i thought of using a dataset from the following website [https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#]


However I've gone with a dataset I found on credit scoring on the Kaggle website, purely because of the greater number of observations available. The training dataset has 150k observations and the test 100k.

Link [https://www.kaggle.com/c/GiveMeSomeCredit]

Targets are unknown in the test dataset. However in order to assess my model , I will spit my training dataset into a training sample of 100000 training and 50000 test, removing the targets and assessing my model selection in this way.

The winning solution was the one that attained the highest area under the curve.
From Kaggle:
The AUC, which is part of performance metric of a logistic regression, is a commonly used evaluation metric for binary classification problems like predicting a Buy or Sell decision (binary decision). The interpretation is that given a random positive observation and negative observation, the AUC gives the proportion of the time you guess which is correct. It is less affected by sample balance than accuracy. A perfect model will score an AUC of 1, while random guessing will score an AUC of around 0.5, a meager 50% chance on each other.


## Structure of this Repo:

### Part 1 - Context

[1.0 - Data Understanding](NOTEBOOKS/0_Business_Understanding.ipynb)

[1.1 - Data Understanding](NOTEBOOKS/1_Data_Understanding.ipynb)

[1.2 - Data Dictionary](NOTEBOOKS/Data Dictionary.xls)

    
### Part 2 - The Data 

[2.1 - Training Data (Original)](DATA/cs-training.csv)

[2.2 - Test Data (Original)](DATA/cs-test.csv)   

[2.3 - Training Data (Pre-Processed)](DATA/training.csv)    

[2.3 - Test Data (Pre-Processed)](DATA/test.csv)  

[2.4 - Data Cleaning](NOTEBOOKS/2_DataCleaning.ipynb)  
    
### Part 3 - Working Files 

[3.1 - Linear Discriminant Analysis](NOTEBOOKS/3_LDA.ipynb)  

[3.2 - Logistic Regression ](NOTEBOOKS/4_LogisticRegression.ipynb)  

[3.3 - Classification and Regression Trees (CART)](NOTEBOOKS/5_CARTS.ipynb)  

[3.4 - Random Forests](NOTEBOOKS/6_RandomForests.ipynb)  

[3.5 - Gradient Boosting](NOTEBOOKS/7_GradientBoosting.ipynb)  

[3.6 - Support Vector Machines (SVM)](NOTEBOOKS/8_SVMs.ipynb)  

[3.7 - Neural Networks](NOTEBOOKS/9_NeuralNetworks.ipynb)

### Part 4 - Presentation 

[4.0 - Presentation](OUTPUT/Data Science Project Presentation.pptx)


### TODO

- [x] Linear Discriminant Analysis
- [x] Logistic Regression
- [x] Classification and Regression Trees
- [x] Random Forests
- [x] Gradient Boosting 
- [ ] Support Vector Machines (Incomplete)
- [ ] Neural Network (Not Started)




