# Credit_Risk_Analysis
## Overview
### Purpose
Creating multiple machine learning tool to classify and predict high and low risk for loans.  Comparing the different machine learning tools to see which model is the least bias and high confidence.  The depedencies we are using is scikit-learn and imbalanced-learn libraries.  The algorithms are SMOTE, randomoversampler, balancedrandomforestclassifier and EasyEnsembleClassifier.  

## Results
### Naive Random Oversampling
  - Precision: High_risk - 0.01 Low_risk - 1.00
    - Low risk has a high precision while the High risk is a very low precision at 0.01.
  - Accuracy: .59
  - Recall: High_risk - 0.57 Low_risk - 0.62
  - F1 score: High_risk - 0.02 Low_risk - 0.76
![1 Naive](https://user-images.githubusercontent.com/101272613/179426565-ec1a7691-ea1c-420e-89a0-1d697757e35c.PNG)

### SMOT Oversampling
  - Precision: High_risk - 0.01 Low_risk - 1.00
    - Low risk has a high precision while the High risk is a very low precision at 0.01.
  - Accuracy: .605
  - Recall: High_risk - 0.61 Low_risk - 0.60
  - F1 score: High_risk - 0.02 Low_risk - 0.75
![2 SMOTE](https://user-images.githubusercontent.com/101272613/179426575-3bb6f14a-18d4-4e82-a1f6-a24473dc1003.PNG)

### Undersampling
  - Precision: High_risk - 0.01 Low_risk - 1.00
    - Low risk has a high precision while the High risk is a very low precision at 0.01.
  - Accuracy: .517
  - Recall: High_risk - 0.62 Low_risk - 0.42
  - F1 score: High_risk - 0.01 Low_risk - 0.58
![3 Undersampling](https://user-images.githubusercontent.com/101272613/179426590-3b7a5c24-8f6e-4fc5-8a76-7be4e7740100.PNG)

  
### Combination (Over and Under) Sampling
  - Precision: High_risk - 0.01 Low_risk - 1.00
    - Low risk has a high precision while the High risk is a very low precision at 0.01.
  - Accuracy: .610
  - Recall: High_risk - 0.67 Low_risk - 0.55 
  - F1 score: High_risk - 0.02 Low_risk - 0.71
![3 Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/101272613/179426589-194e80a7-118a-411e-adbf-16c643a43d80.PNG)

### Balanced Random Forest Classifier
  - Precision: High_risk - 0.01 Low_risk - 1.00
    - Low risk has a high precision while the High risk is a very low precision at 0.01.
  - Accuracy: .59
  - Recall: High_risk - 0.62 Low_risk - 0.42
  - F1 score: High_risk - 0.01 Low_risk - 0.59
![3 Balanced Random Forest Classifier](https://user-images.githubusercontent.com/101272613/179426583-36a3a695-ef2c-4f49-8d41-5d9e8898a00e.PNG)

### Easy Ensemble AdaBoost Classifier
  - Precision: High_risk - 0.73 Low_risk - 1.00
    - Low risk has a high precision while the High risk has a decent amount of 0.73.
  - Accuracy: Unknown due to defunct skilearn version.  Could not produce due to an error. 
  - Recall: High_risk - 0.25 Low_risk - 1.00 
  - F1 score: High_risk - 0.37 Low_risk - 1.00
![4 Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/101272613/179426594-9dcd6ef5-3493-42be-b01b-7a5578d8ba54.PNG)

## Summary
Overall, the best algorithms to use in this instance is the Easy Ensemble AdaBoost Classifier.  It was the only one to produce high_risk precision above .5 while the rest was 

