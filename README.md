# Credit_Risk_Analysis
## Overview of the Credit Risk analysis
Using a credit card credit dataset from LendingClub, we leveraged a series of sampling strategies coupled with the Balanced Random Forest and Easy Ensemble Classifiers to predict credit risk. We were tasked with and will provide an evaluation of the performance of the models while providing a recommedation on if the models should be used to predict credit risk.

## Results
### Balanced Random Forest Classifier
![Balanced Random Forest Classifier.](https://github.com/taxcollecter/Credit_Risk_Analysis/blob/2e2690b17cd806494cfe9a543b1482e34be3db2c/Resources/Balanced%20Random%20Forest%20Classifier.png)

--Balanced Acc: .78

--Precision: .99

--Recall: .91



### Combo Sampling
![Combo Sampling.](https://github.com/taxcollecter/Credit_Risk_Analysis/blob/2e2690b17cd806494cfe9a543b1482e34be3db2c/Resources/Combo%20Sampling.png)

--Balanced Acc: .62

--Precision: .99

--Recall: .54



### Easy Ensemble
![Easy Ensemble.](https://github.com/taxcollecter/Credit_Risk_Analysis/blob/2e2690b17cd806494cfe9a543b1482e34be3db2c/Resources/Easy%20Ensemble.png)

--Balanced Acc: .93

--Precision: .99

--Recall: .94



### Naive Random Oversampling
![Naive Random Oversampling.](https://github.com/taxcollecter/Credit_Risk_Analysis/blob/2e2690b17cd806494cfe9a543b1482e34be3db2c/Resources/Naive%20Random%20Oversampling.png)

--Balanced Acc: .64

--Precision: .99

--Recall: .65



### SMOTE Oversampling
![SMOTE Oversampling.](https://github.com/taxcollecter/Credit_Risk_Analysis/blob/2e2690b17cd806494cfe9a543b1482e34be3db2c/Resources/SMOTE%20Oversampling.png)

--Balanced Acc: .63

--Precision: .99

--Recall: .64



### Undersampling
![Undersampling.](https://github.com/taxcollecter/Credit_Risk_Analysis/blob/2e2690b17cd806494cfe9a543b1482e34be3db2c/Resources/Undersampling.png)

--Balanced Acc: .50

--Precision: .99

--Recall: .44

## Summary
In reviewing the various models, we've pulled out the Balanced Accuracy, Precision, and Recall to highlight their performances. The 4 Sampling approaches all struggledfd with accuracy and Recall. Precision findings were found to be consistent. Regarding the Easy Ensemble and Balanced Random Forest classifiers, they drastically outpeformed the Sampling models, with the Easy Ensemble classifier managing a .93 balance accuracy against a .78 of the BRF. Given the accuracy and precision of the Easy Ensemble classifier, we suggest moving forward with leveraging it to further your efforts around predicting credit risks
