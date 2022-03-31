# Credit Risk Analysis

## Overview
The purpose of this analysis is to employ different machine learning techniques to train and evaluate models with unbalanced classes using the credit card dataset from LendingClub, a peer-to-peer lending service company, to predict credit risk.

## Results
### Deliverable 1: Resampling Models to Predict Credit Risk
#### Naive Random Oversampling
-Accuracy score: 0.8325

-Confusion matrix: ![RandomOverSampler_confusion_matrix](https://user-images.githubusercontent.com/93107507/160961160-7b006588-0296-4c33-9a88-e6d4ede62575.png)

-Imbalanced classification report: ![RandomOverSampler_classification_report](https://user-images.githubusercontent.com/93107507/160961178-f8c5f43e-cf47-4589-beb6-6b4b32455e53.png)

#### SMOTE Oversampling
-Accuracy score: 0.8441

-Confusion matrix: ![SMOTE_confusion_matrix](https://user-images.githubusercontent.com/93107507/160961222-5b5dc1a4-fcff-4369-80b4-2f322b7db397.png)

-Imbalanced classification report:![SMOTE_classification_report](https://user-images.githubusercontent.com/93107507/160961206-9ad075b1-beea-40fb-be4c-43108079df91.png)

#### Cluster Centroid (Undersampling)
-Accuracy score: 0.8441

-Confusion matrix: ![ClusterCentroid_confusion_matrix](https://user-images.githubusercontent.com/93107507/160961251-58f30d8b-e48d-4271-8f79-5bfdc651b765.png)

-Imbalanced classification report: ![ClusterCentroid_classification_imbalanced_report](https://user-images.githubusercontent.com/93107507/160961279-4d902513-cda8-47bc-b5d9-0cd9b240b4ba.png)


### Deliverable 2: Using SMOTEEN algorithm to Predict Credit Risk
#### SMOTEEN 
-Accuracy score: 0.8441

-Confusion matrix:![SMOTEENN_confusion_matrix](https://user-images.githubusercontent.com/93107507/160962858-ed1b8b8d-b9a7-4aba-bd86-5dc4aaba6360.png)


-Imbalanced classification report:![SMOTEENN_classification_report](https://user-images.githubusercontent.com/93107507/160962834-beccff9e-13a7-4712-ad58-609c297c1ee7.png)


### Deliverable 3: Using Ensemble Classifiers to Predict Credit Risk
#### Balanced Random Forest Classifier
-Accuracy score: 0.784

-Confusion matrix:![BalancedRandomForestClassifier_confusion_matrix](https://user-images.githubusercontent.com/93107507/160962906-31089a96-de46-4d66-9865-ccdd570a0c8b.png)

-Imbalanced classification report:![BalancedRandomForestClassifier_classification_report](https://user-images.githubusercontent.com/93107507/160962891-ca529cce-c4e0-496c-b7e5-b5407f66cf50.png)


#### Easy Ensemble Classifer:
-Accuracy score: 0.9316

-Confusion matrix:![EasyEnsembleClassifier_confusion_matrix](https://user-images.githubusercontent.com/93107507/160962942-d332a1ae-df6c-405e-9a4b-154df289dfd7.png)

-Imbalanced classification report:![EasyEnsembleClassifier_classification_report](https://user-images.githubusercontent.com/93107507/160962929-8dcc9f27-9920-49a1-ae8f-d9e87c64b56b.png)

## Summary
The Naive Random Oversampling, SMOTE, Cluster Centroid, and SMOTEENN models are not good models to predict credit risk due to their low F1 and precision scores. The Easy Ensemble Classifier model did the best in predicting credit risk, by having an. f1 score of 0.16, which is higher than the other models explored in this analysis.
