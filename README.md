# Customer Churn Prediction

## Overview
This project predicts customer churn for a telecom company using machine learning. The goal is to identify customers who are likely to stop using the service and provide actionable insights to reduce churn.

## Dataset
The dataset used is the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn) from Kaggle. It contains information about telecom customers and whether they churned or not.

## Project Steps
1. **Exploratory Data Analysis (EDA)**: Analyzed the dataset to understand the distribution of features and their relationship with churn.
2. **Data Preprocessing**: Handled missing values, encoded categorical variables, and scaled numerical features.
3. **Modeling**: Built and evaluated a Random Forest Classifier and a Decision Tree Classifier.
4. **Feature Importance**: Identified the most important features influencing churn.
5. **Hyperparameter Tuning**: Optimized model performance using GridSearchCV.

## Results
- The Random Forest model achieved an accuracy of ~80%.
- Key features influencing churn include tenure, monthly charges, and contract type.
- Decision Trees provided better interpretability and could be tuned for improved performance.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Customer_Churn_Prediction.git
