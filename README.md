# Credit risk classification
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
![Alt text](credit-risk.png)

## Overview of the Analysis

In the banking financial world, it is vitally important to be able to predict whether an individual will be a person who can pay his debts and loans, this in order to maintain a balance between incomes and outcomes.

The data analyzed represents the behavior of a loan debtor, there were columns that could be related to the status of the data, for example the size of the loan, the interest on it, and the income of the applicant, the input of these variables will allow us to say with certainty the status of the loan.

For this, the data went through a pretreatment process, initially recorded as a csv file, it was integrated into a data frame for rework, the feature and lable variables were identified, this only tells us that we are in front of a supervised model, where to train the model well to predict an outcome similar to the label.The data was separated randomly to train the model and to test it, a logical regression model was used, with the integration of a sklearns module, the model was trained with a random state of 1 and then it was tested

## Results

Once model was trained, we input model with the testing data, this will result with all the predictions, but this does not end here, we have to review how much accurable the model is, this is vital, because imagine predicting values on an none accurable model this will lead into bad finnancila banking results, so the results shown as bellow. 

* Model score: 99% : Probably the most important model value, this show what we all this time wanted, how accourable the model is, this number means that 99% percent of the times we imput features into it the prediction will be correct, but we have to review on the next point

* Model Precision: this is very important to know, the model shows to be a little bit less accurable when predicting active status of 1, it means that 85% percent of the times the real status of an loan active, the model will predicted well,on the other hand, the model shows a 100% accouracy with those as label 0 satus on loan.




## Summary
Training a machine learning model to predict whether a person will be a debtor or not is crucial for several reasons. First, it helps financial institutions assess customers' credit risk more accurately, which can reduce the risk of loss due to default. Additionally, it allows for a more efficient allocation of financial resources by identifying clients who are more likely to meet their financial obligations. This can improve the profitability of the institution and contribute to a more stable economy. Finally, it can promote fairer lending practices by relying on objective data rather than subjective biases.
we could also use others models such as:
1. random trees: An extension to decision trees that uses multiple trees to improve prediction accuracy.
2. Support Vector Machines (SVM): These are useful for binary classification problems and can handle linear and non-linear data.
3. Neural networks: Complex models that can capture non-linear relationships between variables and are useful when large amounts of data are available.