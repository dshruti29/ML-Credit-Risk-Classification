# Module 12  -Credit Risk Classification Report



The purpose of this challenge was to build a prediction model that would be able to analyze credit worthiness of borrowers for a bank and to identify potential loan defaults. 
The dataset provided by the bank contained 77,536 entries with seven key indicators. These are listed as follows:

Size of the loan
Interest rate on the loan
Income
Debt_to_Income ratio
number of accounts
Derogatory marks on the borrower's credit report
total debt
loan status indicating a healthy loan with a 0 and a loan in default with a 1.

Based on the value counts of loan status ,there are 2500 out of 75036  in default.
The features and target variable were spearated , to split data in Train,test data respectively.

To complete this analysis, the dataset was first split into training and testing datasets. After instantiating a logistic regression model from scikit-learn, the training data was fit to the model. Predictions of the test data were compared to the given labels. 
To further analyse the dataset , Decision Tree and Randon Tree Forest were also used to classify .

## Results



* Machine Learning Model 1:Logistic Regression
* 
  ![Alt text](Starter_Code/Screenshots/Image1.png?raw=true "Optional Title")



* Machine Learning Model 2:Decision Tree 

* ![Alt text](Starter_Code/Screenshots/Image2.png?raw=true "Optional Title")
  


* Machine Learning Model 3:Random Forest

* ![Alt text](Starter_Code/Screenshots/Image3.png?raw=true "Optional Title")
  

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any.
* All the three models perform well in terms of accuracy . Out of the three Logistic Regression amd Random Tree Forest seem to perform better .
Precision is good for both , but Logistic Regression model does a better job in predicting the Actual -1 . So for this dataset , its recommended.

* Since both models correctly predict healthy loans, it is important to have a model that correctly classifies more high-risk loans, even. The risk associated with misclassifying a healthy loan as high-risk is lower than the risk of not classifying a high-risk loan as such.


