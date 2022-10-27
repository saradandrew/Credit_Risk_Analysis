# Credit_Risk_Analysis

## Overview of the Analysis
In this analysis, different machine learning techniques were used to analyze credit card risk. RandomOverSampler and SMOTE algorithms were used for oversampling while the ClusterCentroids algorithm was used for undersampling credit card data from obtained from LendingClub. Then, BalancedRandomForestClassifier and EasyEnsembleClassifier were used for comparison measure.

## Results
- The balanced accuracy score for the RandomOversampler model is .65, and the overall precision is .99.
- The balanced accuracy score for the SMOTE model is .62, and the overall precision is .99.
- The balanced accuracy score for the ClusterCentroids, model is .51 and the overall precision is .99.
- The balanced accuracy score for the BalancedRandomForestClassifier model is .79, and the overall precision is .99.
- The balanced accuracy score for the EasyEnsembleClassifier model is .93, and the overall precision is .99
- The balanced accuracy score for the SMOTEENN model is .64, and the overall precision is .99.
With all of the models having a precision of .99, the EasyEnsembleClassifier model seems to be the most successful since it has the highest accuracy.

<img width="807" alt="Screen Shot 2022-10-27 at 1 47 52 AM" src="https://user-images.githubusercontent.com/107032720/198212386-7a4464b0-c2c5-48ef-bd81-8d767245f15c.png">


## Summary
Each model used in this analysis returned an almost perfect precision score, but the models with the highest level of accuracy were the BalancedRandomForestClassifier and the EasyEnsemblerClassifier. I would recommend using one of these models for machine learning for most accuracy, especially the EasyEnsembleClassifier.
