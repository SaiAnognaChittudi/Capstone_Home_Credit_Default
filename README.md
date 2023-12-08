# Capstone Home Credit Default Risk Project
![image](https://github.com/SaiAnognaChittudi/Capstone_Home_Credit_Default/assets/144569057/6129692c-1bf8-4695-878c-66b396abef5b)

# Introduction

This project is from the Kaggle competition where the data from Home Credit is provided to find the Home Credit Loan Default risk. Home Credit is dedicated to enhancing financial inclusion for the unbanked population, striving to provide a positive and secure borrowing experience. To ensure a favorable loan experience for this underserved demographic, Home Credit employs alternative data, including telco and transactional information, to assess clients' repayment capacities.

Although Home Credit currently utilizes various statistical and machine learning methods for predictions, they are inviting Kagglers to assist them in fully unleashing the potential of their data. This collaborative effort aims to prevent the rejection of clients capable of repayment to meet that financial gap in society.


# Business Problem

The business problem for the Home Credit Default risk analysis project is to fully harness the potential of the available data to predict client repayment behavior. The core business challenge for Home Credit is to forecast the probability of the target variable precisely, enabling them to extend their services to the broadest possible user base. So, the Goal is to develop a model that predicts whether the loan applicant is at risk of defaulting on the loan.

To combine all the points, the business problem in an overall sense is to find the customers who are likely to default and the customers and their traits with high repayment abilities.

# Project Objective

The project's primary objective is to develop a high-performance machine learning predictive model for the target variable using data provided from multiple sources, thereby facilitating business expansion. This model will be trained from the data available from Kaggle, which are the application data, previous data of customers, Bureau data, and Credit card balance data. Thus, utilizing the data, the machine learning models will learn all the attributes and correlations with respect to the Target Variable. 

 To reiterate in simpler terms, the Project objective is to create a Machine learning model to :
1. Find the individuals who are highly likely to default
2. Find individuals with high repayment abilities to expand Home credit's customer base


# Groups's Solution 

We have built several models on the training data to test the models and find the best model to be presented to the Home Credit. The models that we developed as a group are logistic regression, XG Boost, random forest classifier, and light gradient boosting models. After testing all the models, we found the Light Gradient Boosting and XG Boost models to be good, with 0.92 and 0.91 accuracy, respectively. But considering the Run time, we have declared the LGB as our best model and got the solution for the business problem from the same.

We found from the LGB model that we developed the top features that contribute to the solution, which are External Data Scores provided in the application data and the Annuity-to-Credit Ratio(ACR), which we created from the data during the Feature Engineering phase.

Also, we identified some of the traits of individuals who have high repayment abilities as follows:
1. Married individuals
2. Individuals who own a Car or House
3. Individuals who have a higher education degree

These points are the solution that we have provided as a group for Home Credit, along with providing a Light Gradient Boosting model code for Home Credit to implement as a solution to find the High default risk customers.


# Contribution to Project

I have played a pivotal role in the project by delivering a compelling project introduction that effectively framed the work's context and objectives. I have also skillfully managed outliers using Winsorization techniques, ensuring the integrity and robustness of the data. My analysis of correlation and covariance values, along with the plots for the same, helped with the identification of key features within the dataset for subsequent modeling. Additionally, I have adeptly addressed inaccuracies present in the numerical data by using the Imputation methods.

Taking the initiative to apply the Gradient Boosting model, I went a step further by extending it to the XGBoost model, as the general gradient boosting model is taking too much time to process. Through meticulous hyperparameter tuning using GridSearchCV, the model's performance is significantly improved. My contributions extended beyond individual efforts by actively participating in group discussions and sharing valuable insights derived from the model findings. My approach has enhanced the overall effectiveness of the project's work.


# The business value of Solution

We have compared the basic model, which is logistic regression, to the model that we have selected as the best model, which is the LGB model. For those, we have considered the precision value, which is 0.69 for Logistic regression and for LGB model, it is 0.92

An example is 10000 customers, who are taken as customers who are less likely to default. By using the precision value, we have calculated the prediction of risk of default by using both the logistic and LGB model, which actually has to be 0(Zero) according to the example we have taken.

The predictions are as follows:
Logistic Regression - 3193
LGB Model           - 16

This proves that the LGB model will provide more than 3000 customers to Home Credit, expanding its customer base, which is caused by the use of the LGB Model.
This Business solution perfectly aligns with the Home Credit's motto of reducing the Financial services gap in society.


# Difficulties faced by the Group during the Project

Throughout the Home Credit Risk Analysis project, our team faced several challenges demanding meticulous problem-solving and thoughtful consideration. The first and foremost thing is to run the model on the local machines, as machine learning models take a lot of computation power to run them. Significantly, the Gradient boosting model with the GridSearch Cross-validation method took a look at computational power and took hours to fit the model on training data. 

Another point is managing the Class Imbalance of the Target variable. There is a 1:10 ratio of defaulters to non-defaulters in the data, so reducing it is really important to reduce the Bias in the model. We as a group tried undersampling first, which didn't improve model performance significantly, so we tried SMOTE oversampling, which improved all the model's performances. 

Other than the technical issues, we have struggled to meet the deadlines. There are other subject deadlines along with this project. Most importantly, the job responsibilities of the team members also made it difficult to focus entirely on the project and meet the deadlines. But even with all the difficulties we faced as a group, we managed to move together and get the project completed by the end of the semester.


# Learning from the Project

This project has given me a detailed understanding of how the data will be present in the real world. This provided me with experience in managing the machine learning models as a group and a learning experience in interpreting the results from the model. Significantly, it afforded me a deeper insight into the challenges of imbalanced datasets and underscored the critical importance of effectively addressing class imbalance.

The project also taught me the value of effective collaboration and communication within a team framework. Consistent meetings, transparent task allocation, and harnessing each team member's expertise emerged as essential components for achieving project success, particularly given the project's strict timelines and limited resources.

Finally, the Home Credit Risk Analysis project not only enhanced my comprehension of data science methodologies but also enriched my skill set in handling imbalanced data, integrating diverse data sources, and interpreting intricate machine learning models. The encountered challenges and subsequent learning experiences have served as a driving force, further motivating me to continually refine my data science expertise and contribute to impactful solutions within the field.

