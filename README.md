# Fraud Detection with Machine Learning
This project demonstrates the use of machine learning to detect fraudulent transactions. The system processes raw transaction data, performs feature engineering, and applies machine learning models to predict fraud.

# Key Steps:
Data Ingestion: Loaded raw transaction data from Delta Lake storage (Bronze, Silver, Gold layers).

Feature Engineering: Created time-based, user-level aggregated features, and one-hot encoded categorical variables for location.

Model Training: Split data into training and testing sets, then trained a machine learning model (Random Forest) to classify transactions as fraudulent or not.

Model Evaluation: Evaluated the model using metrics like accuracy, precision, recall, and F1-score.

Deployment: Prepared the model for deployment to predict fraud in new transaction data.

# Technologies Used:
Apache Spark for data processing

Delta Lake for storage

PySpark MLlib for machine learning
