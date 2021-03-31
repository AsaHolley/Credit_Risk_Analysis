# Credit_Risk_Analysis

## Overview of the Analysis ##
In this project we used a credit card credit dataset from LendingClub, a peer-to-peer lending services company, to use supervised machine learning to review credit risk. In the project we oversampled the data using the RandomOverSampler and SMOTE algorithms, and under-sampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and under-sampling using the SMOTEENN algorithm. Finally we compared two new machine learning models that are used to reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, in the analysis.


## Results ##

* **Naive Random OverSampling**
In the Naive Random Oversampling the balanced accuracy score is ~0.64 which means there is some good precitive value in this model, however, tt is not stellar  and therefore for suitabel for data or a project that requires percise models. The precision score is XX and the recall score is XX

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/Naive%20Random%20Oversampling.png)

* **SMOTE Oversampling**

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/SMOTE%20Oversampling.png)

* **Cluster Centroids**

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/ClusterCentroids.png)

* **SMOTEENN** 

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/SMOTEENN.png)

* **Balanced Random Forest Classifer**

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/Balanced%20Random%20Forest%20Classifier.png)

* **Easy Ensemble AdaBoost Classifier**

![](https://github.com/AsaHolley/Credit_Risk_Analysis/blob/main/pictures/Easy%20Ensemble%20AdaBoost%20Classifier.png)


## Summary ##
