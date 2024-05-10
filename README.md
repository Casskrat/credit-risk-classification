# credit-risk-classification
## Overview of the Analysis

In this analysis we look into factors that contribute to loan risk. There are 77536 observations with 7 different covariates considered. We split this data into a training and testing dataset in order to fit our our logistic regression model.
## Results

Machine Learning Model:
    * Precision: 94% (The logisitic regression model predicts the healthy loans with 100% accuracy and a high-risk loan with 87% accuracy.)
    * Accuracy: 99% (overall model accuracy)
    * Recall: 94% (The logisitic regression model had 100% recall in predicting healthy loans, but 89% recall in predicting high-risk loans.)

## Summary

I would recommend this model for use to predict healthy lones due to the fact that there is no false positives, however I would add in a secondary model when wanting to predict for high-risk loans. Since for this model the accuracy is only 87% we would want a model that maybe allowed for more false positives to balance out the false negatives. 
