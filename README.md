# capstone-project-Ecommerce-and-Retail.

Overview

Timely payments are crucial for businesses to maintain financial stability. This project aims to predict whether a payment will be delayed or on time using machine learning.

Objective

Build a classification model to predict late payments using various machine learning algorithms and fine-tune the best-performing model.

Data Description

The dataset includes payment-related details such as receipt method, customer details, invoice information, due dates, and payment terms.

Approach

Data Preprocessing

Converted datetime columns into meaningful features.

Dropped unnecessary columns.

Encoded categorical variables.

Feature Selection

Used Random Forest and RFE to select the most relevant features.

Handling Class Imbalance

Applied SMOTE to balance the dataset.

Feature Scaling

Standardized numerical features for better model performance.

Model Training & Evaluation

Tested Logistic Regression, Random Forest, Gradient Boosting, SVM, and KNN.

Gradient Boosting performed the best after hyperparameter tuning.

Results & Limitations

The model can predict delayed payments with high accuracy.

Some categorical features were lost due to encoding.

Model performance may be affected by biases in the dataset.

Future Work

Experiment with deep learning models.

Improve data balancing techniques.

Add more relevant features.

Deploy the model for real-time predictions.

Author: Sre
