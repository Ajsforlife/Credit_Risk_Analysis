# Credit Risk Analysis
## Overview
### Purpose

The sole purpose of this analysis was to figure out which sampling method provided the best balanced accuracy score, precision score, and recall score. There were 6 machine learning models used throughout this analysis and the best scores acquired were from the AdaBooster classifier Analysis. Each model ran provided slightly better results but the AdaBooster privoded the best overall results. There are 4 models used RandomOverSampler, SMOTE, ClusterCentroids, and SMOTEENN. There are 2 machine learning models used also which are BalancedRandomForstClassifier and EasyEnsembleClassifer aka AdaBooster.
The formulas used for balanced accuracy precision and recall are as follows:

The formula for Accuracy = (TP + TN) / (TP + TN + FP + FN) where TP is True Positives, TN is True Negatives, FP is False Positives, and FN is False Negatives

The formula for Precision = TP/(TP + FP) where TP is True Positives and FP is False Positives.

The formula for Recall = TP/(TP + FN).

##Results
### Deliverable 1

![image1](https://github.com/Ajsforlife/Credit_Risk_Analysis/blob/main/credit_analysis_pictures/deliverable%201-1.png)

Naive Random Oversampling (Picture Above) provided the following results:

-Accuracy: .6572

-Precision: .01

-Recall: .69

![image2](https://github.com/Ajsforlife/Credit_Risk_Analysis/blob/main/credit_analysis_pictures/deliverable%201-2.png)

SMOTE Oversampling (Picture Above) provided the following results:

-Accuracy: .6478

-Precision: .01

-Recall: .61

![image3](https://github.com/Ajsforlife/Credit_Risk_Analysis/blob/main/credit_analysis_pictures/deliverable1-3.png)

ClusterCentroids Undersampling (Picture Above) provided the following results:

-Accuracy: .5444

-Precision: .01

-Recall: .69

### Deliverable 2

![image4](https://github.com/Ajsforlife/Credit_Risk_Analysis/blob/main/credit_analysis_pictures/deliverable2.png)

SMOTEENN Oversampling (Picture Above) provided the following results:

-Accuracy: .6706

-Precision: .01

-Recall: .77

### Deliverable 3

![image5](https://github.com/Ajsforlife/Credit_Risk_Analysis/blob/main/credit_analysis_pictures/deliverable3-1.png)

Balanced Random Forest Classifer (Picture Above) provided the following results:

-Accuracy: .7885

-Precision: .03

-Recall: .70

Featured list in descending order:
![iamge6](https://github.com/Ajsforlife/Credit_Risk_Analysis/blob/main/credit_analysis_pictures/deliverable3-2.png)

![image7](https://github.com/Ajsforlife/Credit_Risk_Analysis/blob/main/credit_analysis_pictures/deliverable%203-3.png)

Easy Ensemble AdaBoost Classifier (Picture Above) provided the following results:

-Accuracy: .9317

-Precision: .09

-Recall: .92

## Summary

### Synopsis

There were 6 different models used to perform this analysis. Of those 6 the BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms performed the best with drastically better accuracy and percision scores. The SMOTEENN model performed somewhat decently with higher accuracy and recall scores compared to the undersampling, oversampling and SMOTE models. If I were to use one model in particular it would be the Easy Ensemble Classifier model solely because it returned the best results with ease of use. Where the balanced random forest classifier provided better then average results but provide a little more difficult to use based on versions of the kits used and depreciation of those kits in newer version.

### Recommendations





