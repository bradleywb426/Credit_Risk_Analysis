# Credit Risk Analysis

## Overview

In this challenge, we used different techniques to train and evaluate models to handle the unbalanced classes of good and risky credit loans. The dataset from LendingClub was both over and under sampled, and then sampled using a combinatorial approach of over and under sampling. Then, two machine learning models were employed to predict credit risk.

## Results

- Naive Random Oversampling

  - Balanced Accuracy Score: ~65.73%
  
  - Precision Score: ~1% in assessments for high risk loans, and ~100% in assessments for low risk loans
  
  - Recall Score: ~71% in assessments for high risk loans, ~60% in assessments for low risk loans
  
<img src="https://github.com/bradleywb426/Credit_Risk_Analysis/blob/main/Images/sample1.png" width="600">

-----

- SMOTE Oversampling

  - Balanced Accuracy Score: ~66.22%
  
  - Precision Score: ~1% in assessments for high risk loans, and ~100% in assessments for low risk loans
  
  - Recall Score: ~63% in assessments for high risk loans, and ~69% in assessments for low risk loans
  
<img src="https://github.com/bradleywb426/Credit_Risk_Analysis/blob/main/Images/sample2.png" width="600">

-----

- Cluster Centroids Undersampling

  - Balanced Accuracy Score: ~54.43%
  
  - Precision Score: ~1% in assessments for high risk loans, and ~100% in assessments for low risk loans
  
  - Recall Score: ~69% in assessments for high risk loans, and ~40% in assessments for low risk loans
  
<img src="https://github.com/bradleywb426/Credit_Risk_Analysis/blob/main/Images/sample3.png" width="600">

-----

- SMOTEENN Sampling

  - Balanced Accuracy Score: ~68.76%
  
  - Precision Score: ~1% in assessments for high risk loans, and ~100% in assessments for low risk loans
  
  - Recall Score: ~80% in assessments for high risk loans, and ~57% in assessments for low risk loans
  
<img src="https://github.com/bradleywb426/Credit_Risk_Analysis/blob/main/Images/sample4.png" width="600">

-----

- Balanced Random Forest Classifier

  - Balanced Accuracy Score: ~78.78%
  
  - Precision Score: ~4% in assessments for high risk loans, and ~100% in assessments for low risk loans
  
  - Recall Score: ~67% in assessments for high risk loans, and ~91% in assessments for low risk loans
  
<img src="https://github.com/bradleywb426/Credit_Risk_Analysis/blob/main/Images/ensemble1.png" width="600">

-----

- Easy Ensemble AdaBoost Classifier

  - Balanced Accuracy Score: ~92.54%
  
  - Precision Score: ~7% in assessments for high risk loans, and ~100% in assessments for low risk loans
  
  - Recall Score: ~91% in assessments for high risk loans, and ~94% in assessments for low risk loans
  
<img src="https://github.com/bradleywb426/Credit_Risk_Analysis/blob/main/Images/ensemble2.png" width="600">

-----

## Summary

The Oversampling methods had a balanced accuracy of around 66%, while the Undersampling method had a balanced accuracy of around 54%. The combinatory sampling method had a higher balanced accuracy of about 69%. Of the ensemble methods, the Balanced Random Forest had a balanced accuracy of about 79% and the Easy Ensemble AdaBoost had a balanced accuracy of about 93%. Following these results, the Easy Ensemble AdaBoost would be recommened due to its high accuracy with data.
