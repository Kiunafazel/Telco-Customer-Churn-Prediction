# Telco Customer Churn Prediction

A Machine Learning project that predicts whether a customer is likely to leave a telecommunications company.

## Project Overview

Customer churn prediction helps companies identify customers who may stop using their services. This project uses customer data to predict whether a customer will leave the company.

## Dataset

The dataset contains information about telecommunications customers, including:

- Customer demographics
- Internet and phone services
- Contract information
- Payment methods
- Monthly and total charges
- Customer churn status

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Data Preprocessing

The following steps were performed:

- Handling missing values
- Converting data types
- Encoding categorical features
- Removing unnecessary columns
- Splitting data into training and testing sets
- Feature scaling using StandardScaler

## Machine Learning Models

Three classification models were tested:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)

## Model Evaluation

The models were evaluated using:

- ROC AUC Score
- Confusion Matrix

### Results

| Model | Training ROC AUC | Test ROC AUC |
|---|---:|---:|
| Logistic Regression | 84.50% | 85.75% |
| Decision Tree | 84.98% | 84.16% |
| KNN | 89.27% | 77.86% |

Logistic Regression achieved the best test ROC AUC score among the three models.

## Conclusion

This project demonstrates how Machine Learning can be used to predict customer churn and help telecommunications companies better understand customer behavior.

The results show that Logistic Regression performed best on the test dataset.

## Author

Kiana Ebrahimi Fazel

[GitHub Profile](https://github.com/Kiunafazel)
