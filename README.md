# Predict_Loan_Campaign
## Data Description:
The dataset contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank 
(mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan).
## Domain
Banking
## Context
This case is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. 
This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with a minimal budget.
## Objective:
The classification goal is to predict the likelihood of a liability customer buying personal loans
## Packages Used
* Pandas
* Numpy
* Matplotlib/Seaborn
* sklearn
## Exploratory Data Analysis

### ![Personal Loan Vs. Annual Income ($000)](/Images/pic1.png)        ![Personal Loan Vs. Family Size](/Images/pic2.png)
### ![Confusion Matrix](/Images/pic3.png)

 precision    recall  f1-score   support

           0       0.99      0.87      0.92      1364
           1       0.40      0.88      0.55       136

    accuracy                           0.87      1500
 
 ### Business Understanding and Inference:
 
 #### The ROC_AUC score is high, 0.874, Also the Recall score is high here 0.882 -- So, we can say that this Logit Model is performing well in distinguishing positives from negative classes with less False Negatives.
