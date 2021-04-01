# Credit_Risk_Analysis

## Overview of the Analysis
In this project we used a credit card credit dataset from LendingClub, a peer-to-peer lending services company, to use supervised machine learning to review credit risk. In the project we oversampled the data using the RandomOverSampler and SMOTE algorithms, and under-sampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and under-sampling using the SMOTEENN algorithm. Finally we compared two new machine learning models that are used to reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, in the analysis.


## Results ##

* **Naive Random OverSampling:**
In the Naive Random Oversampling model the balanced accuracy score is ~0.64 which means there is some predictive value in this model, however, it is not stellar and therefore is unsuitable for data or a project that requires need highly accurate models. The precision score is .01 for the high-risk credit profiles meaning the model is not good at predicting those outcomes and the recall score on average, for both credit profile types, is better at 0.62 meaning the model does have some predictive capability, but still on the low end for a well calibrated model.

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/Naive%20Random%20Oversampling.png)

* **SMOTE Oversampling:**
In the SMOTE Oversampling model the balanced accurary score is ~0.65, which is roughly the same as the Naive Random Oversampling model and therrefore shows some predictive value. The precision score is again .01 for hte hihg-risk credit profiles meaning the model is not good at predicting these outcomes. The recall score, on average is a bit higher than the Naive Random OverSampling at ~0.69 meaning the modes does have some decent predictive capabilities, albeit still not particulary precise. 

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/SMOTE%20Oversampling.png)

* **Cluster Centroids:**
In the Cluster Centroids model the balanced accurary score is lower than the previous two models coming in at ~0.54 which does not have good predictive power, its only slightly better than random. The precision score of ~0.01 for the high-risk credit profiles is in line with what is described for the first two models. The recall score on average, for both credit profile types,came in at ~0.4 meaning the model does not good predictive capability.

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/ClusterCentroids.png)

* **SMOTEENN:** 
In this combination of over and under-sampling model, the balanced accuracy score came in at ~0.65 which was about equal with the SMOTE model. The preceision was very low for the high risk credit profiles similar to the above 3 models at 0.01. The recall score was 0.56, which means the model does not have a high rate of predictive capibility. 

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/SMOTEENN.png)

* **Balanced Random Forest Classifer:**
In the Balanced Random Forest Classifer model, the balanced accuracy score is ~0.77, which is better than the previous 4 models tested and means there is a far amount of predictive pwoer in the model. Furthermore, the precision for the high-risk credit profiles is 0.04, which while not good is still better than the previously tested models. The recall is impressive with an average recall of ~0.90 indicating this is good model for prediciting credit risk.

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/Balanced%20Random%20Forest%20Classifier.png)

* **Easy Ensemble AdaBoost Classifier:**
In this model the balanced accuracy score was 

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/Easy%20Ensemble%20AdaBoost%20Classifier.png)


## Summary ##
