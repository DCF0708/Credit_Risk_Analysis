# Credit_Risk_Analysis
</br>
</br>

## Overview
The following report is an assessment of 6 different machine learning models effectiveness in predicting credit risk. Each method was executed on the same credit card credit dataset from a popular peer-to-peer lending company. The results of each model are shown as they exist in code and their outputs are then summarized below. 



## Results
</br>
</br>

### RandomOverSampler
!(RandomOverSampler)[/images/1.png]

Balanced accuracy score: 

Precision: 0.65
    
- High Risk: 0.01

Recall Scores:
    
- High Risk: 0.71
- Low Risk: 0.58

### SMOTE
!(SMOTE)[/images/2.png]

Balanced accuracy score: 0.66

Precision:
    
- High Risk: .01

Recall Scores:
    
- High Risk: 0.63
- Low Risk: 0.68

### ClusterCentroids
!(ClusterCentroids)[/images/3.png]

Balanced accuracy score: 0.54

Precision:
    
- High Risk: 0.01

Recall Scores:
    
- High Risk: 0.69
- Low Risk: 0.40

### SMOTEENN
!(SMOTEENN)[/images/4.png]

Balanced accuracy score: 0.67

Precision:
    
- High Risk: 0.01

Recall Scores:
    
- High Risk: 0.73
- Low Risk: 0.60

### BalancedRandomForestClassifier
!(BalancedRandomForestClassifier)[/images/5.png]

Balanced accuracy score: 0.79

Precision:
    
- High Risk: 0.03

Recall Scores:
    
- High Risk: 0.70
- Low Risk: 0.87

### EasyEnsembleClassifier
!(EasyEnsembleClassifier)[/images/6.png]

Balanced accuracy score: 0.93

Precision:
    
- High Risk: 0.09

Recall Scores:
    
- High Risk: 0.92
- Low Risk: 0.94

## Summary 
Analysis of the results concludes that the EasyEnsembleClassifier Machine Learning method created the best model for prediction of credit risk. The Balanced Accuracy Score is the highest out of the population. Precision of the method follows suit leading the population with a precision score of 0.09. The Recall scores are 0.92 and 0.94 which firmly solidifies the EasyEnsembleClassifier Machine Learning model as the most effective predictor of credit risk out of the test group.