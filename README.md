# Churn-in-Telecom
![image](https://github.com/evamwende/Churn-in-Telecom/assets/82519367/98d61d54-0d36-4ff7-a8eb-19b32041f7d5)


## Business Understanding
ChurnBusters Inc. is a pioneering telecommunications analytics firm dedicated to assisting phone service providers in reducing customer churn rates. In the telecom industry, churn refers to customers switching between service providers or canceling subscriptions. Typically, a customer is considered churned when a certain period has elapsed since their last interaction with the service. 

*Objective*: Develop an effective classification model for predicting customer churn in a telecommunications firm.

## Data Understanding
The [dataset](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset) offers a comprehensive view of customer information in a telecommunication firm, encompassing attributes such as customer location (state), account length, area code, international plan status, voicemail plan status, call details (daytime, evening, nighttime, and international), customer service calls, and most notably, the churn indicator. It provides a rich source of information for understanding customer behavior and factors influencing churn.

## EDA 
This sections seeks to understand the characteristics of the data variables as single units and its relation with other variables.
These figures are a representation of some univariate, bivariate and multivariate analysis on the data set.


![image](https://github.com/evamwende/Churn-in-Telecom/assets/82519367/629a2a2b-e059-4765-a846-e12132904757)


![image](https://github.com/evamwende/Churn-in-Telecom/assets/82519367/2db75f5f-4c93-4f38-a93c-3d7fbb322c17)


![image](https://github.com/evamwende/Churn-in-Telecom/assets/82519367/64cdeb12-d6ba-4c57-bf26-5a112911fe4f)

## Pre-processing
This section generally prepares our data set for modelling. For example the visualization of our target column revealed an classification imbalance in our data set.


![image](https://github.com/evamwende/Churn-in-Telecom/assets/82519367/36c6a2a7-fce1-4be3-bf20-eb851c3fcd00)


The [Workbook](https://github.com/evamwende/Churn-in-Telecom/blob/main/Workbook.ipynb) offers a detailed code solving the classification imbalance through SMOTE to acheive this:


![image](https://github.com/evamwende/Churn-in-Telecom/assets/82519367/d02d4f23-0f28-4cf5-82e0-ae55f82ef16a)


## Modelling
Three models were used in this project i.e Logistic Regression,  K-Nearest Neighbors (KNN) and Decision tree model just to try and determine the best suited for predicting our target variable. Tuning of hyperparameters for both the KNN model and Decesion Tree shed sime light on enhanced the effectiveness of these models

## Conclusion and Recommendation
In conclusion, our model evaluations indicated that the tuned Decision Tree model was the optimal choice for accurately predicting customer churn. It offered a well-rounded performance with high accuracy, precision, recall, and F1-score, striking a practical balance between capturing churned customers and maintaining good precision. This made it a reliable and robust option for improving customer churn predictions, ensuring that businesses could effectively identify and address potential churn cases.

