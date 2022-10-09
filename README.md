# Credit_Risk_Analysis
Module 17 Challenge
## Overview of Project
For this project we tried to do 6 different machine learning models to predict credit risk of different potential clients. First we had to clean the data and split it into training and testing data. The six models used were oversampling, SMOTE Oversampling, Undersampling, a combination of over and undersampling, Ensemble Learners, and finally easy Ensembling, however i could not get the last 2 for Deliverble 3 to work. But the confusion matrices for the first 4 came out well.
## Results 
### Oversampling
The first model we used was Oversampling where we imported the RandomOverSampler package. The classification report can be seen in the screenshot.
![image](https://user-images.githubusercontent.com/105249779/194737532-22fc663f-d0d5-4bd1-91df-4b569c4347e3.png)
### SMOTE Oversampling 
The second model was oversampling from the SMOTE package. The classification report can be seen below.
![image](https://user-images.githubusercontent.com/105249779/194737563-67423b09-22be-4a8a-9bec-fd84e218bc1d.png)
### Undersampling
The third model was Undersampling using the ClusterCentroids Package. The classification report can be seen below.
![image](https://user-images.githubusercontent.com/105249779/194737595-d2a9e2d3-663c-4207-a6c4-59cc24f41446.png)
### Over and Under Sampling
The fourth model we used SMOTEENN to create a combination of oversampling and undersampling. The resulting classification report can be seen below.
![image](https://user-images.githubusercontent.com/105249779/194737657-75ee41a6-334a-4509-9ff4-8a74dfdf7531.png)
### Deliverable 3
I could not get Deliverable 3 to work so the outcome for these models cannot be seen.
## Summary
The results for the first 4 models can be seen above but the accuracy scores for the models are as follows: Model 1 .662, model 2 .656, model 3 .544, model 4 .639. Model 1 (Oversampling) had the highest accuracy score at 66.2% closly followed by model 2 (SMOTE oversampling) at 65.6%. The other 2 models performed lower. I would say 66.2% is a good accuracy score for credit score and i would choose model 1 (Oversampling) for this project to determine credit risk.
