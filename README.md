# Credit_Risk_Analysis

## Analysis Overview
The purpose of this analysis was to use Python to build, and evaluate the effectiveness of, several machine learning models to predict credit risk.

To complete this analysis, I used a total of six machine learning models in the following ways:
1. Oversampled the data with Naive Random Oversample using RandomOverSampler 
2. Oversampled the data with SMOTE oversampling.
3. Undersampled the data using the ClusterCentroids algorithm.
4. Used a combined approach for oversampling and undersampling with the SMOTEENN algorithm.
5. Compared BalancedRandomForestClassifier and EasyEnsembleClassifier, two machine learning models that are meant to reduce bias.

## Results
In this results section, I will share the balanced accuracy scores, precision, and recall scores of all six machine learning models used in this analysis.

### RandomOverSampler Model
<br><img src="ROS_BAS"></img></br>
<br><img src="ROS_CRI"></img></br>
Balanced Accuracy Score: 64%
High Risk has a precision of only 1% with 61% recall and a low F1 score of .02.
Low risk has a high precision of 100%, recall of 66%, and a high F1 score of .8. This is due to the high number in the Low Risk population.

### SMOTE Oversampling