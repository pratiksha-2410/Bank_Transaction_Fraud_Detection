# Bank Transaction Fraud Detection System


## Executive Summary
**Financial fraud results in billions of dollars in annual losses globally. This project presents a production-oriented Machine Learning solution designed to detect fraudulent bank transactions with high recall and controlled false positive rates.**

**The system leverages advanced feature engineering, class imbalance handling, and model optimization techniques to identify high-risk transactions in near real-time.**

### This project demonstrates strong competencies in:

**Applied Machine Learning**

**Risk Analytics**

**Feature Engineering**

**Model Evaluation for Imbalanced Data**

**Business-Oriented Data Science**

## Business Objective
**The goal is to build a fraud detection model that:**

**Maximizes Fraud Detection Rate (Recall)**

**Minimizes False Positives**

**Reduces financial loss**

**Enhances trust and compliance**

**Supports scalable deployment in banking systems**

# Dataset Overview
**The dataset consists of anonymized transactional records including:**

**Transaction ID**

**Customer ID**

**Transaction Amount**

**Timestamp**

**Merchant Category**

**Account Balance**

**Transaction Type**

**Fraud Indicator (Target Variable)**

**Fraud cases represent a minority class, creating a highly imbalanced classification problem.**

# Technical Approach
## Data Preprocessing
Missing value handling

Label encoding / One-hot encoding

Feature scaling (StandardScaler)

Outlier treatment

Train-test split with stratification

## Exploratory Data Analysis (EDA)
Fraud vs Legitimate transaction distribution

Amount distribution analysis

Correlation matrix

Time-based anomaly trends

Customer behavior patterns

## Feature Engineering
Transaction frequency per customer

Rolling average transaction value

Time difference between transactions

Behavioral deviation features

High-risk merchant indicators

## Class Imbalance Handling
To address skewed data:

SMOTE (Synthetic Minority Oversampling Technique)

Class-weight tuning

Threshold optimization

## Model Development
Models implemented and compared:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

XGBoost (if applicable)

Hyperparameter tuning performed using GridSearchCV.

# Model Evaluation Metrics
**Since fraud detection is an imbalanced classification problem, accuracy alone is insufficient.**

Primary metrics used:

Precision

Recall

F1-Score

ROC-AUC

Confusion Matrix

Precision-Recall Curve

Priority was given to maximizing Recall to reduce financial risk from undetected fraud.



# Business Impact
**If deployed in a real banking environment, this system can:**

Reduce fraud-related financial losses

Improve transaction monitoring efficiency

Automate risk scoring

Support regulatory compliance

# Key Skills Demonstrated
Advanced Feature Engineering

Imbalanced Classification Handling

Hyperparameter Optimization

Model Evaluation Strategy


👩‍💻 Author
<br>
Pratiksha Bagwale Zagade
<br>
Aspiring Data Scientist | Python | Data Analysis | Business Insights






