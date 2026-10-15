# Customer Churn Prediction Using Machine Learning

## Overview
This project uses machine learning classification algorithms to predict whether a telecommunications customer is likely to churn based on demographic information, service subscriptions, contract details, and billing information.

## Objectives
- Explore and understand customer churn data.
- Perform data cleaning and exploratory data analysis (EDA).
- Handle class imbalance using SMOTE.
- Train and compare multiple machine learning classifiers.
- Evaluate model performance and generate predictions for new customer records.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Google Colab

## Machine Learning Workflow
1. Data loading and cleaning
2. Exploratory data analysis
3. Categorical feature encoding
4. Training and test data splitting
5. Class imbalance handling
6. Model training and cross-validation
7. Model evaluation
8. Model serialization and prediction

## Models
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

## Evaluation
Model performance is assessed using accuracy, a confusion matrix, precision, recall, F1-score, and classification reports.

Final performance results will be added after model evaluation.

## How to Run
1. Open `Customer_Churn_Prediction.ipynb` in Google Colab.
2. Obtain the dataset from its original source, subject to its usage terms.
3. Upload the CSV file and update the dataset path if necessary.
4. Install any missing dependencies.
5. Run the notebook cells in order.

## Future Improvements
- Hyperparameter tuning
- Stratified cross-validation with SMOTE applied within each training fold
- Comparison of oversampling and undersampling
- Overfitting analysis
- Improved handling of unseen categorical values

## Author
Yokitha Rathinarasa
