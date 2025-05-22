# Hotel-Reservation-Cancellation-Prediction

Hotel Reservation Cancellation Prediction

Introduction

This repository contains the code, data, and findings from the Hotel Reservation Cancellation Prediction project. Using various machine learning models, this project aims to accurately predict cancellations of hotel reservations, providing valuable insights for improving hotel revenue management, operational efficiency, and customer service.

Objective

The primary goal is to build and evaluate predictive models to determine the likelihood of hotel reservation cancellations based on historical data.

Dataset

The dataset used for this project is sourced from Kaggle and includes details about customer demographics, booking behaviors, reservation specifics, and cancellation statuses. Key preprocessing steps performed:

Dropped unnecessary columns (Booking_ID).

Removed infrequent categorical labels.

Converted categorical features using Label Encoding.

Split the data into training (80%) and test (20%) subsets.

Machine Learning Models Implemented

The following models were explored:

Random Forest Classifier

XGBoost Classifier

LightGBM Classifier

Multi-Layer Perceptron (MLP) Classifier

Evaluation Metrics

Model performance was evaluated using:

Accuracy

ROC AUC (Receiver Operating Characteristic - Area Under Curve)

Confusion Matrix

Permutation Feature Importance

Cross-validation

Results

Random Forest achieved the highest accuracy (90.25%) and ROC AUC (0.99), effectively predicting cancellations.

XGBoost (ROC AUC: 0.97) and LightGBM (ROC AUC: 0.96) also demonstrated strong performance.

MLP Classifier showed decent predictive capability but lagged slightly behind the ensemble methods.

Key Insights

lead_time was identified as a crucial factor influencing cancellations.

The Random Forest model provided clear feature importance insights, highlighting significant predictors.

Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn

XGBoost

LightGBM

Future Directions

Improve data collection methodologies.

Include additional external data (customer feedback, market trends).

Enhance model interpretability using SHAP values.

Address data imbalance issues using sampling methods.

Validate models with varied datasets to test robustness and adaptability.
