# Credit Risk Analysis

## Overview
### Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, 6 different machine learning models were applied to the dataset to determine which is the best machine learning model to predict credit risk.

## Results
### Using resampling, the imbalanced-learn and scikit-learn libraries were used to build and evaluate the following six machine learning models:

* Oversample with RandomOverSampler algorithm
Balanced accuracy score:
Precision score:
Recall scorce:

![RandomOverSampler_Accuracy.png](images/RandomOverSampler_Accuracy.png)
![RandomOverSampler_Report.png](images/RandomOverSampler_Report.png)

* Oversample with SMOTE algorithm
![SMOTE_Accuracy.png](images/SMOTE_Accuracy.png)
![SMOTE_Report.png](images/SMOTE_Report.png)
Balanced accuracy score:
Precision score:
Recall scorce:

* Undersample with ClusterCentroids algorithm
Balanced accuracy score:
Precision score:
Recall scorce:

![ClusterCentroids_Accuracy.png](images/ClusterCentroids_Accuracy.png)
![ClusterCentroids_Report.png](images/ClusterCentroids_Report.png)

* Over and undersampling with SMOTEENN algorithm
Balanced accuracy score:
Precision score:
Recall scorce:

![SMOTE_Accuracy.png](images/SMOTE_Accuracy.png)
![SMOTE_Report.png](images/SMOTE_Report.png)

* Reduce bias with BalancedRandomForestClassifier
Balanced accuracy score:
Precision score:
Recall scorce:

![BalancedRandomForest_Accuracy](images/BalancedRandomForest_Accuracy.png)
![BalancedRandomForest_Report](images/BalancedRandomForest_Report.png)

* Reduce bias with EasyEnsembleClassifier
Balanced accuracy score:
Precision score:
Recall scorce:

![EasyEnsemble_Accuracy](images/EasyEnsemble_Accuracy.png)
![EasyEnsemble_Report](images/EasyEnsemble_Report.png)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning. 

