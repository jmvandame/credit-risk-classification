# credit-risk-classification
Module 20- Report 

## Overview of the Analysis

* The purpose of the analysis is to create a model that can determine creditworthiness of loan borrowers.
* We used historical lending details from a peer-to-peer lending services company. 
* In our analysis we identified "Loan Status" as the Dependant variable (y value), and the independent variables (x values) to include the other available loan features including; loan size, intrest rate, borrower income, debt to income ratio, number of accounts and derogatory marks. 
* We first split our data to traning and test sets. Then, define our dependent and independent variables. Next, we create logistic regression model and fit our original data to this model. Trained model is used to make predictions. Lastly, we evaluate the model`s performance.
* Two diffeent Logistic Regression models were created by using the original data set and randomy over resampled data set (to get rid of the imbalances). In the end, their results -which was gathered with scikit-learn library- were compared.

## Results

* Machine Learning Model 1- Original Data Set:
* Description of Model 1 Accuracy, Precision, and Recall scores.
* Balanced Accuracy Score: 0.9442676901753825

![image](https://github.com/jmvandame/credit-risk-classification/assets/119906562/6018faf2-f908-4d1a-b5ff-3f73fda09ed7)


* Machine Learning Model 2- Randomly Oversampled Data:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

* Training Data Score: 0.9941016646031091
* Testing Data Score: 0.9952022286421791
* Balanced Accuracy Score: 0.9959744975744975

![image](https://github.com/jmvandame/credit-risk-classification/assets/119906562/de6b4e9a-4dd9-4e52-9783-f6393300af33)

## Summary

Analysis of the data collected can be used to predict loan health. By applying random oversampling the data gets higher balanced and accuracy scores for healthy loans. The model can pedict both healthy and risky loans with accuracy, but higher results were produced for healthy loans. We may need to review more data to ensure we don't have a high flase-positive rate (i.e. healthy loans the should be high-risk). 
