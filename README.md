# Bank Telemarketing Campaign Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a customer will subscribe to a bank term deposit after a telemarketing campaign using machine learning techniques.

The goal is to analyze customer profiles and campaign-related information to identify patterns that influence customer decisions and build a predictive model to support data-driven marketing strategies.

This project follows an end-to-end machine learning workflow including data exploration, preprocessing, feature engineering, model development, and evaluation.


## 🎯 Problem Statement

Bank marketing campaigns involve contacting customers to promote financial products such as term deposits.

However, not every customer responds positively, which can lead to inefficient resource utilization.

The objective of this project is to build a machine learning model that predicts whether a customer is likely to subscribe to a term deposit based on historical customer and campaign data.

This prediction can help improve campaign targeting and decision-making.


## 📂 Dataset

Dataset Source:
UCI Machine Learning Repository - Bank Marketing Dataset

The dataset contains customer demographic information, financial details, and campaign-related attributes.

### Key Features:

**Customer Information**
- Age
- Job
- Marital status
- Education

**Financial Information**
- Account balance
- Housing loan status
- Personal loan status

**Campaign Information**
- Contact method
- Number of contacts performed
- Previous campaign outcome
- Campaign duration


### Target Variable:

`y`

- Yes → Customer subscribed to term deposit
- No → Customer did not subscribe


## 🧠 Approach

### 1. Data Understanding
- Loaded and explored the dataset structure
- Analyzed feature distributions
- Studied relationships between customer attributes and subscription outcomes


### 2. Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Performed feature scaling
- Prepared data for machine learning models


### 3. Exploratory Data Analysis (EDA)
- Analyzed customer characteristics
- Identified important factors influencing subscription decisions
- Visualized trends and patterns


### 4. Model Development

The project explores machine learning approaches for binary classification:

- Logistic Regression
- Decision Tree
- Random Forest
- Multi-Layer Perceptron (MLP)


### 5. Model Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix


## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Jupyter Notebook


## 📁 Project Structure
