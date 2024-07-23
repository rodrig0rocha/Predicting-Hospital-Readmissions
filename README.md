# Overview
Hospital readmissions represent a significant challenge in the healthcare sector, both as an indicator of care quality and a driver of escalating costs. When a patient is re-admitted to the hospital within a short period after discharge, it not only indicates potential gaps in care but also adds to the financial burden on the healthcare system. In particular, readmissions of diabetic patients have been noted to contribute significantly to these costs. Therefore, being able to predict such readmissions can lead to improved patient care and substantial cost savings.

# Models and Techniques
In this project, several machine learning models were implemented and evaluated to predict hospital readmissions for diabetic patients. Each model was built using a consistent preprocessing pipeline for fair comparison.
I have explored various machine learning models and techniques in this project, including:

Complement Naive Bayes 
Gaussian Naive Bayes 
Decision Tree 
Logistic Regression 
Random Forest
Linear Support Vector Classifier 
Gradient Boosting
AdaBoost
CatBoost

Feature engineering and selection techniques were also employed to enhance model performance.

# Evaluation Metrics
### Class Imbalance
The dataset used in this project is unbalanced, with a significant disparity between the number of instances in the majority class (non-readmitted patients) and the minority class (readmitted patients). This imbalance poses challenges for model evaluation, as traditional accuracy may not fully reflect the model's performance, especially on the minority class.
### Binary Classification Metrics
For binary classification tasks, where the goal is to predict whether a patient will be readmitted within 30 days or not, the F1 Score (Binary) is used as a primary evaluation metric. The F1 Score balances precision and recall, providing a single metric that reflects both the ability to correctly identify positive cases and the proportion of true positive cases out of all predicted positives.
### Multiclass Classification Metrics
In cases where the classification problem involves multiple classes, such as predicting various types of readmissions or other categories, the F1 Score (Weighted) is used. This metric accounts for class imbalance by considering the support (the number of true instances for each class) and averaging the F1 Scores of each class proportionally.


