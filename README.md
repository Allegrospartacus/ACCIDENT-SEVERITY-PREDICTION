# ACCIDENT-SEVERITY-PREDICTION
Objective: The goal of this project is to predict the severity of road traffic accidents using machine learning models. The project focuses on data preprocessing, feature engineering, handling class imbalance, and comparing multiple classification algorithms.

Tech Stack:

Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn (SMOTE)

Models: Random Forest, Logistic Regression, Gradient Boosting, Support Vector Machine
Evaluation: Accuracy, Precision, Recall, F1 Score, Confusion Matrix


Key Steps:

Data Cleaning: Handled missing data by replacing categorical missing values with 'Unknown' and imputing numeric data with the mode.

Feature Engineering: Extracted new features like 'Hour of Day' from the 'Time' column.

Categorical Encoding: Used Label Encoding for ordinal features and One-Hot Encoding for nominal features.

Imbalanced Data Handling: Applied SMOTENC to balance the dataset for better model performance.

Modeling: Trained and evaluated multiple classification models (Random Forest, Logistic Regression, Gradient Boosting, SVM).

Feature Selection: Selected the top 50 features using SelectKBest with chi-squared statistic.

Results: Random Forest achieved the highest performance in terms of accuracy and other classification metrics. Visualized the confusion matrix and feature importance for a better understanding of the model.
