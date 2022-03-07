# Credit_risk_analysis
# Overview 
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I have  employed different techniques to train and evaluate models with unbalanced classes. I have used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

# Purpose
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I have oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I have used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. lastly, I have evaluated the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results
<img width="1092" alt="image" src="https://user-images.githubusercontent.com/92557075/156973831-02f172f6-c6b7-4abf-8678-0e7ac2fb5a5d.png">

<img width="1122" alt="image" src="https://user-images.githubusercontent.com/92557075/156973862-24499216-42a5-46a5-b72c-20dad86ad459.png">

<img width="1076" alt="image" src="https://user-images.githubusercontent.com/92557075/156973903-61ed4782-d4df-4934-9769-cc67de81e27e.png">


This new assignment consists of three technical analysis deliverables and a written report. You will submit the following:

1. Deliverable 1: Use Resampling Models to Predict Credit Risk
2. Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
3. Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
4. Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

