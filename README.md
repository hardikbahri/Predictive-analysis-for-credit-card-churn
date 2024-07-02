# Predictive Analysis for Credit Card Customer Churn

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This project aims to predict customer churn for a credit card service using various machine learning algorithms. The analysis includes data preprocessing, feature engineering, model training, and evaluation. The primary goal is to identify factors contributing to customer churn and predict whether a customer is likely to churn based on their attributes and behavior.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)

## Project Overview

Customer churn is a significant issue for businesses, especially in the financial sector. Predicting churn helps in taking proactive measures to retain customers. This project leverages machine learning techniques to predict whether a credit card customer will churn or not. 

The analysis involves:
- Data preprocessing and cleaning
- Feature engineering
- Balancing the dataset
- Applying various machine learning models
- Evaluating model performance

## Dataset

The dataset used in this project is `bankchurn.csv`, sourced from Kaggle. It contains the following columns:

- Attrition_Flag
- Customer_Age
- Gender
- Dependent_count
- Education_Level
- Marital_Status
- Income_Category
- Card_Category
- Months_on_book
- Total_Relationship_Count
- Months_Inactive_12_mon
- Contacts_Count_12_mon
- Credit_Limit
- Total_Revolving_Bal
- Avg_Open_To_Buy
- Total_Amt_Chng_Q4_Q1
- Total_Trans_Amt
- Total_Trans_Ct
- Total_Ct_Chng_Q4_Q1
- Avg_Utilization_Ratio

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hardikbahri/Predictive-analysis-for-credit-card-churn.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Predictive-analysis-for-credit-card-churn
   ```

3. Create a virtual environment and activate it:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the analysis, open the Jupyter Notebook:

```bash
jupyter notebook Predictive-analysis-customer-churn.ipynb
```

Follow the steps in the notebook to understand the data preprocessing, feature engineering, model training, and evaluation process.

## Modeling

The project applies the following machine learning algorithms to predict customer churn:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Each model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Results

The results of the analysis show the effectiveness of different models in predicting customer churn. The detailed evaluation and comparison of the models are provided in the notebook. 

