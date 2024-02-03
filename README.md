# Sampling_Assignment
## SAMPLING REPORT
## Dataset Overview
The dataset comprises 772 entries categorized into two classes: class 0 and class 1. However, it is imbalanced, with 763 instances belonging to class 0 and only 9 to class 1. To address this imbalance, the Synthetic Minority Oversampling Technique (SMOTE) is employed. SMOTE involves randomly selecting a point from the minority class and determining its k-nearest neighbors.

## Sample Size Computation
The sample size (n) is computed using the formula: n=Z².p.(1-p)/E², where n represents the sample size, p denotes the standard deviation, Z is the z-score, and E is the margin of error.

## Utilized Sampling Techniques

Simple Random Sampling
Systematic Random Sampling
Cluster Sampling
Bootstrap Sampling

## Models for Assessment
Logistic Regression
Support Vector Classifier
XGBoost Classifier
Random Forest
Gaussian Naive Bayes
Accuracy Scores

## Accuracy Scores

| Sampling Techniques | Model 1 (LR) | Model 2 (SVC) | Model 3 (XGB) | Model 4 (RF) | Model 5 (GB) |
| --- | --- | --- | --- | --- | --- |
| *Sample 1 (Simple Random)* | 0.87 | 0.93 | 0.94 | 0.99 | 0.78 |
| *Sample 2 (Systematic Random)* | 0.89 | 0.94 | 0.97 | 0.97 | 0.81 |
| *Sample 3 (Cluster Sampling)* | 0.93 | 0.97 | 0.99 | 1 (overfit) | 0.83 |
| *Sample 4 (Bootstrap Sampling)* | 0.95 | 0.95 | 0.96 | 1 (overfit) | 0.87 |

## Outcome
Among the sampling techniques employed, Bootstrap Sampling proves to be the most effective.

Submitted by
Harbandana (102103187) 3CO7
