# Sampling-Methods

Performance Analysis of Machine Learning Models with Different Sampling Techniques

This repository contains the performance analysis of five machine learning models (M1 to M5) using various sampling techniques (Sampling1 to Sampling5). The goal is to assess the accuracy of each model with different techniques and determine the best-performing sampling methods for each model.

Models and Sampling Techniques

Models:
M1: Random Forest Classifier
M2: Logistic Regression
M3: Support Vector Classifier (SVC)
M4: Decision Tree Classifier
M5: K-Nearest Neighbors (KNN)

Sampling Techniques:
Sampling1: Random Undersampling
Sampling2: Random Over-Sampling
Sampling3: SMOTE (Synthetic Minority Over-sampling Technique)
Sampling4: Borderline-SMOTE
Sampling5: NearMiss

Results and Observations
The table below summarizes the accuracy results for each model using different sampling techniques:

Model	Sampling1	Sampling2	Sampling3	Sampling4	Sampling5
M1	X.XX	1.00	X.XX	X.XX	X.XX
M2	X.XX	X.XX	X.XX	X.XX	1.00
M3	X.XX	X.XX	X.XX	X.XX	1.00
M4	X.XX	0.993	X.XX	X.XX	X.XX
M5	X.XX	X.XX	X.XX	X.XX	1.00
Note: "X.XX" represents accuracy values that are not the best performing for that particular model.

Best Performing Sampling Techniques:
M1 (Random Forest Classifier): The best performance was achieved using Sampling2 (Random Over-Sampling) with an accuracy of 1.00.

Interpretation: Random Over-Sampling performed well, as it helps when the model requires more balanced data to learn better.
M2 (Logistic Regression): The best performance was achieved using Sampling5 (NearMiss) with an accuracy of 1.00.

Interpretation: NearMiss sampling helped by removing certain majority class instances, improving classification for the Logistic Regression model.
M3 (SVC): The best performance was achieved using Sampling5 (NearMiss) with an accuracy of 1.00.

Interpretation: Similar to M2, NearMiss worked well by balancing the dataset, reducing noise, and aiding in better classification for SVC.
M4 (Decision Tree Classifier): The best performance was achieved using Sampling2 (Random Over-Sampling) with an accuracy of 0.993.

Interpretation: Random Over-Sampling benefited the Decision Tree model, as decision trees tend to perform better with more balanced data.
M5 (KNN): The best performance was achieved using Sampling5 (NearMiss) with an accuracy of 1.00.

Interpretation: KNN models tend to struggle with imbalanced datasets, so NearMiss (undersampling) helped improve accuracy.

Conclusion
Best Sampling Techniques:
Random Over-Sampling (Sampling2) performed best for Random Forest and Decision Tree models.
NearMiss (Sampling5) performed best for Logistic Regression, SVC, and KNN models.
SMOTE-based Methods (Sampling3 & Sampling4):
SMOTE and Borderline-SMOTE showed decent results but were not the top performers for any of the models.
