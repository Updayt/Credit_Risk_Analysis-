# Credit_Risk_Analysis

## Overview of the analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we employed different techniques to train and evaluate models with unbalanced classes.
## Resources
- Data:  LoanStats_2019Q1.csv

- Software: Python, Anaconda, Jupyter Notebook 
## Results 
Naive Random Oversampling:

![naive-acc](https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/naive-acc.PNG)

![naive-report](https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/naive-report.PNG)

-	Balanced Accuracy: 65%
-	Precision: High Risk .01, Low Risk 1.00
-	Recall: High Risk .71, Low Risk .58

SMOTE Oversampling:

![smote-acc](https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/smote-acc.PNG)

![smote-report](https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/smote-report.PNG)

-	Balanced Accuracy: 66%
-	Precision: High Risk .01, Low Risk 1.00
-	Recall: High Risk .63, Low Risk .68

Undersampling CluseterCentroid:

![ cluster-under-acc]( https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/cluster-under-acc.PNG)

![ cluster-under-acc](https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/cluster-under-report.PNG)

-	Balanced Accuracy: 66%
-	Precision: High Risk .01, Low Risk 1.00
-	Recall: High Risk .69, Low Risk .40


SMOTEENN Combination-Over and Under Sampling:

![ Over-under-acc]( https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/Over-under-acc.PNG)

![ Over-under-report]( https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/Over-under-report.PNG)

-	Balanced Accuracy: 54%
-	Precision: High Risk .01, Low Risk 1.00
-	Recall: High Risk .72, Low Risk .57

Balanced Random Forest Classifier:

![ bala-acc]( https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/bala-acc.PNG)

![ bala-report]( https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/bala-report.PNG)

-	Balanced Accuracy: 83%
-	Precision: High Risk .03, Low Risk 1.00
-	Recall: High Risk .77, Low Risk .88

Easy Ensemble AdaBoost Classifier: 

![ easy-acc]( https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/easy-acc.PNG)

![ easy-report]( https://github.com/NickFoley47/Credit_Risk_Analysis/blob/main/pics/easy-report.PNG)

-	Balanced Accuracy: 93%
-	Precision: High Risk .07, Low Risk 1.00
-	Recall: High Risk .91, Low Risk .95


## Summary: 
The model I would recommend would be the Easy Ensemble model. The accuracy is 93% and the recall/precision have a good balance. For credit risk, we want an realistic accuracy and we want recall/precision to have a balance between them  to allow the best possibility to predict credit risk. 
