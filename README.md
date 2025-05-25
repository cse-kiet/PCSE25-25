## Title of Project:[A Study to Evaluate Effects of Data Poisoning on Machine Learning Model]

##Team Members:
Deepanshu Mishra

Gaurav Kumar

Ashish Prasad

## Steps for Execution:
1) Dataset Selection & Preparation
     Collected and preprocessed five datasets: Email (Spam), Banking, Diabetes, Heart Attack, and Iris.
     Applied encoding, missing value treatment, normalization, and vectorization (TF-IDF for text data).

2) Baseline Model Training
     Trained four ML models (SVM, Logistic Regression, Random Forest, Decision Tree) on clean datasets.
     Tuned hyperparameters using Grid Search with 5-fold cross-validation.

3) Label Poisoning Simulation
     Introduced label flipping at 5%, 10%, and 20% levels on the training data.
     Retained original test set for performance evaluation.

4) Model Retraining & Evaluation
     Re-trained the same models with poisoned datasets.
     Compared performance using metrics like Accuracy, Precision, Recall, and F1-Score.

5) Robustness Analysis
     Visualized performance drop across models and datasets.
     Ranked classifiers based on resilience to poisoning.

## Checklist:
1. Final Project Report
2. Certificate VII Semester (Dated: December 2024).
3. Certificate VIII Semester (Dated: May 2025).
4. Synopsis
5. Final Presentation
6. Source Code
7. README (This file)
