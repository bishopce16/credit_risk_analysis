# credit_risk_analysis

An analysis to build and evaluate a dataset from LendingClub to discover credit risk using Supervised Machine Learning Algorithms. 

---

## Overview of the analysis: 

The purpose of this project is analyzing a dataset from LendingClub to evaluate several Machine Learning models to predict credit risk. Using Supervised Machine Learning because the data includes a labeled outcome. The dataset is unbalanced as the number of good loans offsets the number of risky loans. To balance out the classification problem to improve accuracy score and predictions several Machine Learning algorithms were employed to resample the data. The algorithms include: RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier. 

---
## Resources:

Data source: [LoanStats_2019Q1.csv](Module-17-Challenge-Resources/LoanStats_2019Q1.csv)

Tools: Python, Scikit Learn, Imbalanced Learn, Juypter Notebook, Pandas, Mechine Learning, Visual Studio Code

---

## Results: 
![valuecount](images/valuecount.png)
![training_data](images/training_data.png)

Oversampling:
![oversampling_count](images/oversampling_count.png)

* RandomOverSampler Model

![oversampling_accuracy](images/oversampling_accuracy.png)
![oversampling_confusion_matrix](images/oversampling_confusion_matrix.png)
![oversampling_class_report](images/oversampling_class_report.png)

* Synthetic Minority Oversampling Technique (SMOTE) Model

![SMOTE_os_accuracy](images/SMOTE_os_accuracy.png)
![SMOTE_os_confusion_matrix](images/SMOTE_os_confusion_matrix.png)
![SMOTE_os_class_report](images/SMOTE_os_class_report.png)

Undersampling:
![undersampling_count](images/undersampling_count.png)

* ClusterCentroids Model

![undersampling_cc_accuracy](images/undersampling_cc_accuracy.png)
![undersampling_cc_cunfusion_matrix](images/undersampling_cc_cunfusion_matrix.png)
![undersampling_cc_class_report](images/undersampling_cc_class_report.png)

Combination Sampling
![SMOTEENN_count](images/SMOTEENN_count.png)

* Synthetic Minority Oversampling Technique plus Edited NearestNeighbors (SMOTEENN) Model

![SMOTEENN_accuracy](images/SMOTEENN_accuracy.png)
![SMOTEENN_cunfusion_matrix](images/SMOTEENN_cunfusion_matrix.png)
![SMOTEENN_class_report](images/SMOTEENN_class_report.png)

Ensemble Classifiers:
![brfc_count](images/brfc_count.png)

* BalancedRandomForestClassifier Model

![brfc_accuracy](images/brfc_accuracy.png)
![brfc_cunfusion_matrix](images/brfc_cunfusion_matrix.png)
![brfc_class_report](images/brfc_class_report.png)
![brfc_feature_impotance](images/brfc_feature_impotance.png)

* EasyEnsembleClassifier Model 

![eec_accuracy](images/eec_accuracy.png)
![eec_cunfusion_matrix](images/eec_cunfusion_matrix.png)
![eec_class_report](images/eec_class_report.png)

---

## Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 
If you do not recommend any of the models, justify your reasoning.

---