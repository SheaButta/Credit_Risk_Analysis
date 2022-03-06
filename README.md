# Credit_Risk_Analysis

![](https://github.com/SheaButta/Credit_Risk_Analysis/blob/main/Images/creditrisk.jpg)

## Overview 
The purpose of this project is to assist my client with predicting credit card risk utilizing Machine Learning (ML).  Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes.
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm.
As always, my analysis followed the data analysis principles of (1) Determine the number of rows and columns; (2) Data types used; and (3) Is the data readable?

__Client Deliverables:__
- Deliverable 1: Use Resampling Models to Predict Credit Risk
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk


## Resources
The resouces used for this analysis included;
- LendingClub Credit Card Dataset
- Jupyter Notebook
- Python 


## Results
All sprints were completed as scheduled and I delivered on all client expectations/results. The below images will describe and visualize the balanced accuracy scores and the precision and recall scores of all six machine learning models.


### Deliverable 1: Use Resampling Models to Predict Credit Risk.  This deliverable required me to load the LendingClub data for analysis using ***Resampling Models to Predict Credit Risk***. 

## Naive Random Oversampling

Based on the results below, the balanced accuracy score is 62%, the precision is 99% and the recall is 65%.

![](https://github.com/SheaButta/Credit_Risk_Analysis/blob/main/Images/Deliverable1_NaiveRandomOversampling.PNG)


### Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

## SMOTE Oversampling

Based on the results below, the balanced accuracy score is 65%, the precision is 99% and the recall is 66%.

![](https://github.com/SheaButta/Credit_Risk_Analysis/blob/main/Images/Deliverable1_SmoteOversampling.PNG)

## Undersampling

Based on the results below, the balanced accuracy score is 51%, the precision is 99% and the recall is 54%.

![](https://github.com/SheaButta/Credit_Risk_Analysis/blob/main/Images/Deliverable1_Undersampling.PNG)

## Combination (Over and Under) Sampling

Based on the results below, the balanced accuracy score is 62%, the precision is 99% and the recall is 54%.

![](https://github.com/SheaButta/Credit_Risk_Analysis/blob/main/Images/Deliverable1_Combination_OverUnder.PNG)


### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

Based on the results below, the balanced accuracy score is 93%, the precision is 99% and the recall is 94%.

![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/Deliverable3_Ensemble.PNG)


## Summary
The models used to preform credit risk appear to show some weakness; however, the ensemble models appear to show improvements with sensitivity.  The ensemble model produced a recall of 94% which appear to detect high credit risks.  I would recommend 
using all models since the precision seems to be low.
