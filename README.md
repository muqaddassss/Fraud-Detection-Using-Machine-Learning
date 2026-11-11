# Fraud Detection Using Machine Learning

## Project Overview
This project focuses on detecting fraudulent financial transactions using Machine Learning techniques. The main goal is to identify suspicious transactions while handling a highly imbalanced dataset, where fraudulent transactions represent a very small percentage of the total data.

Two classification models, Logistic Regression and Random Forest, are trained and evaluated to compare their performance in detecting fraudulent transactions.

## Objectives
- Analyse and understand the imbalance in the dataset.
- Perform Exploratory Data Analysis (EDA).
- Identify patterns in fraudulent and non-fraudulent transactions.
- Handle class imbalance using SMOTE.
- Build and compare machine learning classification models.
- Evaluate model performance using appropriate metrics.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook / Google Colab

## Dataset
The project uses the **Credit Card Fraud Detection** dataset from Kaggle.

- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Non-Fraudulent Transactions: 284,315

**Dataset Link:** [Credit Card Fraud Detection – Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Project Workflow

### 1. Data Loading and Exploration
- Loaded the dataset using Pandas.
- Checked dataset shape, data types, and missing values.
- Analysed the distribution of fraudulent and non-fraudulent transactions.

### 2. Exploratory Data Analysis (EDA)
- Visualised transaction amounts for both classes.
- Analysed transaction patterns across hourly intervals.
- Used charts to understand differences between fraud and normal transactions.

### 3. Handling Class Imbalance
- Identified the highly imbalanced nature of the dataset.
- Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the training data.
- Used a stratified train-test split to maintain class distribution.

### 4. Model Building
Trained two classification models:
- Logistic Regression
- Random Forest Classifier

### 5. Model Evaluation
Evaluated both models using:
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curve

These metrics help assess how effectively each model identifies fraudulent transactions.

### 6. Feature Importance
Analysed Random Forest feature importance to identify which features contributed most to fraud detection.

### 7. Scalability Discussion
Explored how a fraud detection system could handle large transaction volumes using technologies such as Kafka, Apache Spark, and cloud-based infrastructure.

## Key Learning Outcomes
- Understanding classification problems and imbalanced datasets.
- Learning why accuracy alone is not sufficient for fraud detection.
- Applying SMOTE to handle class imbalance.
- Training and comparing multiple classification models.
- Understanding the importance of Precision and Recall.
- Evaluating models using classification metrics and visualisations.
- Exploring scalability considerations for real-world fraud detection systems.

## Conclusion
This project provided practical experience in building a machine learning pipeline for fraud detection. It helped strengthen my understanding of data preprocessing, handling imbalanced datasets, model training, and evaluation. It also highlighted the importance of choosing suitable evaluation metrics when working with real-world classification problems.

---
