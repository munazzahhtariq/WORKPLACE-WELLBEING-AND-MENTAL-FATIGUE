# WORKPLACE-WELLBEING-AND-MENTAL-FATIGUE
A machine learning-based binary classification system that predicts workplace stress using survey data with multiple models including logistic regression, decision trees, and custom neural networks.

## Project Overview
This project focuses on predicting workplace stress levels using machine learning techniques. It uses survey-based tabular data to classify whether an individual is experiencing stress or not.

The system includes data preprocessing, feature engineering, exploratory data analysis (EDA), multiple machine learning models, model comparison, and a simple interactive interface for prediction.

---

## Objective
To build a **binary classification system** that can:
- Analyze workplace survey data
- Detect patterns related to mental fatigue and stress
- Predict whether an individual is stressed or not (Yes/No)
- Provide a real-time interactive prediction interface

---

## Workflow

### 1. Data Collection
- Survey-based tabular dataset
- Includes workplace, lifestyle, and psychological attributes

### 2. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling and normalization

### 3. Feature Engineering
- Selection of important features
- Conversion of survey responses into numerical format

### 4. Exploratory Data Analysis (EDA)
- Data visualization
- Correlation analysis
- Identification of stress-related patterns

---

## Machine Learning Models Used

### 🔹 Logistic Regression Models
- Logistic Regression (C = 0.1)
- Logistic Regression (C = 1)
- Logistic Regression (C = 10)

---

### 🔹 Decision Tree Models
- Decision Tree (Max Depth = 3)
- Decision Tree (Max Depth = 5)
- Decision Tree (Max Depth = 10)

---

### 🔹 Custom Neural Network Models
- Model 1: 1 hidden layer with 32 neurons
- Model 2: 2 hidden layers with 64 neurons and 32 neurons
- Model 3: Same architecture as Model 2 with Adam optimizer and learning rate = 0.001

---

## Model Evaluation & Comparison
All models were trained and evaluated based on performance metrics such as accuracy and generalization ability.

- Logistic Regression models were compared across different regularization strengths (C values)
- Decision Tree models were compared across different depths
- Neural network models were compared across different architectures and optimization settings
- Final model selection was done based on best overall performance

---

## User Interface
A simple widget-based interface was developed to:
- Take user survey inputs
- Process inputs in real time
- Predict whether the individual is experiencing stress or not

---

## Problem Type
- **Binary Classification Problem**
  - Output: Stress / No Stress

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib / Seaborn  
- Widgets (for UI)

---

## Key Features
- End-to-end ML pipeline
- Multiple model comparisons (Logistic, Decision Tree, Neural Networks)
- Hyperparameter tuning (C values, tree depth, learning rate)
- Data preprocessing and EDA
- Real-time prediction interface

---

## Outcome
This project demonstrates a complete machine learning pipeline for workplace stress detection using multiple models and systematic comparison to identify the best-performing classifier.

---
