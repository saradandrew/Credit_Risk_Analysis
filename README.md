# Credit_Risk_Analysis

## Overview of the Analysis
In this analysis, different machine learning techniques were used to analyze credit card risk. RandomOverSampler, SMOTE, and SMOTEENN algorithms were used for oversampling while the ClusterCentroids algorithm was used for undersampling the credit card data obtained from LendingClub. Then, BalancedRandomForestClassifier and EasyEnsembleClassifier were used for comparison measure.

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
Each model used in this analysis returned an almost perfect precision score, but the models with the highest level of accuracy were the BalancedRandomForestClassifier and the EasyEnsemblerClassifier. I would recommend using one of these models for machine learning for most accuracy, especially the EasyEnsembleClassifier. I would not recommend using the ClusterCentroids model since this model's accuracy score was only slightly over 50%.

<img width="810" alt="Screen Shot 2022-10-27 at 1 59 43 AM" src="https://user-images.githubusercontent.com/107032720/198213430-f49f0288-80e5-4e27-b74a-bb0e03cffa8f.png">
