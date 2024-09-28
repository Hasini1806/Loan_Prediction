# Loan_Prediction Using Classification Algorithms 

Overview
----------------------
This project aims to build a predictive model that classifies loan applications as approved or rejected based on various factors using machine learning classification algorithms. We utilize multiple classification techniques such as K-Nearest Neighbors (KNN), Random Forest, Decision Trees, and Kernel Support Vector Machine (SVM), along with hyperparameter tuning methods such as K-Fold Cross Validation and Grid Search to optimize the performance of these models.

Dataset
-------------------
The dataset contains information about loan applicants and their status, including features such as:

Applicant Income

Coapplicant Income

Loan Amount

Loan Term

Credit History

Property Area

Dependents

The target variable is Loan_Status, where the labels are either Yes (loan approved) or No (loan not approved).

You can download the dataset [here](https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction) or use any suitable loan prediction dataset.

Project Workflow
----------------------
Data Preprocessing:
-----------------
Handling missing values

Encoding categorical variables

Feature scaling for algorithms like KNN and SVM

Imputing missing values using statistical methods such as mode and mean

Exploratory Data Analysis:

Visualizing relationships between features:
----------------------
Checking for class imbalance and applying techniques like SMOTE for balancing classes.

Model Building:
---------------------
Classification algorithms implemented:

K-Nearest Neighbors (KNN)

Decision Trees

Random Forest

Kernel SVM

Hyperparameter Tuning:
--------------------

K-Fold Cross Validation: Applied to evaluate models and ensure stable performance across multiple folds of the data.

Grid Search: Used for finding the optimal hyperparameters (e.g., number of neighbors for KNN, number of trees for Random Forest, kernel type for SVM).
Model Evaluation:

Metrics used for evaluating the models include:
-----------

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Results:
---------

The performance of each model is evaluated based on the following metrics:

Accuracy: Percentage of correct predictions

Precision: Ability to correctly identify positive labels

Recall: Ability to capture all true positives

F1-Score: Harmonic mean of precision and recall

The final model selection is based on evaluating these metrics and cross-validation results.

Conclusion:
--------------

The project demonstrates the application of multiple classification algorithms to predict loan approval. Hyperparameter tuning through K-Fold Cross Validation and Grid Search improves model performance. The best model is selected based on a combination of accuracy, precision, recall, and F1-score.



