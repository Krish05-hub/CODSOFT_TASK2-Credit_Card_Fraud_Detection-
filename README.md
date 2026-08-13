# Credit Card Fraud Detection

## Internship Task

This project was developed as part of the CodSoft Machine Learning Internship.

## Objective

The objective of this project is to build a machine learning model that identifies fraudulent credit card transactions from legitimate transactions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models

The following models were trained and compared:

1. Logistic Regression
2. Decision Tree
3. Random Forest

## Approach

1. Loaded separate training and testing datasets
2. Inspected missing values and class distribution
3. Removed transactions with missing target labels
4. Extracted useful transaction time and customer age features
5. Encoded categorical variables
6. Scaled numerical features
7. Handled missing feature values using preprocessing
8. Trained three machine learning models
9. Compared accuracy, precision, recall and F1-score
10. Evaluated the final model using a classification report and confusion matrix
11. Tested the model on a sample transaction
12. Saved the final model and preprocessing pipeline

## Class Imbalance

The dataset contains significantly more legitimate transactions than fraudulent transactions. Therefore, precision, recall and F1-score were considered alongside accuracy when evaluating the models.

## Final Model

Decision Tree was selected as the final model because it achieved the highest F1-score and recall among the evaluated models.

## Results

The Decision Tree achieved approximately:

- Accuracy: 98.36%
- Precision: 19.25%
- Recall: 85.29%
- F1-Score: 31.41%

## Project Files

- `CODSOFT_Task2_Credit_Card_Fraud_Detection.ipynb` — Complete implementation
- `fraud_detection_model.pkl` — Trained Decision Tree model
- `fraud_preprocessor.pkl` — Preprocessing pipeline

## Internship

CodSoft Machine Learning Internship

Task 2 — Credit Card Fraud Detection
