# Capstone Home Credit Default Risk Project
![image](https://github.com/SaiAnognaChittudi/Capstone_Home_Credit_Default/assets/144569057/6129692c-1bf8-4695-878c-66b396abef5b)

# Introduction

This project is form the Kaggle competition where the data from the Home Credit is provided for finding the Home Credit Loan Default risk. Home Credit is dedicated to enhancing financial inclusion for the unbanked population, striving to provide a positive and secure borrowing experience. To ensure a favorable loan experience for this underserved demographic, Home Credit employs alternative data, including telco and transactional information, to assess clients' repayment capacities. 

Although Home Credit currently utilizes various statistical and machine learning methods for predictions, they are inviting Kagglers to assist them in fully unleashing the potential of their data. This collaborative effort aims to prevent the rejection of clients capable of repayment to meet that financial gap in the society.

# Business Problem

The business problem for the Home Credit Default risk analysis project is to fully harness the potential of the available data to predict client repayment behavior. The core business challenge for Home Credit is to precisely forecast the probability of the target variable, enabling them to extend their services to the broadest possible user base. So the Goal is to develop a model that predicts the whether the loan applicant is at a risk to default the loan or not.

To combine all the points the business problem in an overall sense is to find the customers who are likely to default and also finding the customers and their traits who have high repayment abilities.

# Project Objective

The project's primary objective is to develop a high-performance machine learning predictive model for the target variable using data provided from multiple sources, thereby facilitating business expansion. This model will be trained from the data available from the kaggle which are the appication data, previous data of customers, Bureau data and Credit card balance data. Thus utilizing the data the machine learing models will learn all the attributes and correlations with respect to the Target Variable. 

 To reitterate in simpler terms, the Project objective is to create a Machine learning model to :
1. Find the individuals who are highly likely to default
2. Find the individuals with high repayment abilities to expand the Home credit's customer base

# Groups's Solution 

We have bulit several models on the training data to test the models and find the best model that can be presented to the Home Credit. The models that we as a group developed are Logistic Regression, XG Boost, Random Forst Classifier and Light Gradient Boosting Models. After testing all the model, we found that Light Gradient Boosting and XG Boost models to be good with 0.92 and 0.91 accuracy respectively. But considering the Run time, we have declared the LGB as our best model and got the solution for the business problem from the same.

We found from the LGB model that we developed the top features which contributes for the solution which are External Data Scores provided in the application data, the Annuity-to-Credit Ratio(ACR) which we have created from the data during the Feature Engineering phase.

Also, we identified some of the traits of individuals who have high repayment abilities are as follows:
1. Married individuals
2. Individuals who own a Car or House
3. Individuals who have a higher education degree

These points are the solution that we have provided as a group for the Home Credit along with providing a Light Gradient Boosting model code for the Home Credit to implement as a solution to find the High default risk customers.

# Contribution to Project











