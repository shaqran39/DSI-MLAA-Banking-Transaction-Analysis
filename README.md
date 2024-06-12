# DSI-MLAA-Banking-Transaction-Analysis

This repository contains the implementation and analysis of a banking transactions analysis project conducted by Group 7 for the 36106 - Machine Learning Algorithms and Applications course at the University of Technology Sydney.

## Project Details
- **Group 7 Members:**
  - **Astha Dangol** (Student ID: 25173651)
  - **Rakibul Hassan Rejon** (Student ID: 24880419)
  - **Shaqran Bin Saleh** (Student ID: 25010238)
  - **Fahad Amjad** (Student ID: 25116928)
- **Course:** 36106 - Machine Learning Algorithms and Applications
- **Program:** Master of Data Science and Innovation
- **University:** University of Technology Sydney
- **Date:** 24/05/2024

## Table of Contents
1. [Executive Summary](#executive-summary)
2. [Business Understanding](#business-understanding)
3. [Data Understanding](#data-understanding)
4. [Data Preparation](#data-preparation)
5. [Modeling](#modeling)
6. [Evaluation](#evaluation)
7. [Business Impact and Benefits](#business-impact-and-benefits)
8. [Data Privacy and Ethical Concerns](#data-privacy-and-ethical-concerns)
9. [Collaboration](#collaboration)
10. [Conclusion](#conclusion)
11. [References](#references)

## Executive Summary
This project leverages three years of transactional data to develop machine learning solutions for key business needs in banking. Our solutions aim to improve customer experience, marketing efficiency, and fraud detection.

**Key Problem Statements:**
- **Financial Empowerment for Customers:** Predicting monthly spending to help customers budget better.
- **Fraud Detection:** Identifying fraudulent transactions to mitigate financial risks.
- **Targeted Marketing:** Segmenting customers based on spending behaviors for targeted marketing.
- **Proactive Customer Support:** Detecting abnormal spending patterns to assist customers proactively.

## Business Understanding
### Business Use Cases
1. **Customer Financial Management:** Predicting customer spending for the next month.
2. **Fraud Detection and Risk Mitigation:** Identifying potentially fraudulent transactions.
3. **Targeted Marketing Strategies:** Segmenting customers based on spending behaviors.
4. **Proactive Customer Support:** Anomaly detection for abnormal spending patterns.

**Key Objectives:**
- **Business Case 1:** Develop regression models for spending prediction.
- **Business Case 2:** Create predictive models for fraud detection.
- **Business Case 3:** Implement clustering algorithms for customer segmentation.
- **Business Case 4:** Develop anomaly detection systems for early fraud detection.

## Data Understanding
### Data Sources and Description
The dataset includes transaction records and customer information from the bank's internal systems. It contains:
- **Transaction Details:** Credit card number, account number, transaction number, Unix timestamp, category, amount, fraud status, merchant name, and geographic coordinates.
- **Customer Information:** Social security number, name, address, gender, job title, and date of birth.

### Exploratory Data Analysis (EDA)
Performed EDA to understand the data distribution, relationships, and key variables influencing spending behavior and fraud detection.

## Data Preparation
### Data Cleaning and Feature Engineering
- **Handling Missing Values:** Imputed or removed missing values.
- **Encoding Categorical Variables:** Applied one-hot encoding and frequency encoding.
- **Feature Scaling:** Standardized numerical features.
- **Feature Selection:** Selected important features based on correlation analysis.

### Data Splitting
Split the data into training, validation, and testing sets to ensure effective model training and evaluation.

## Modeling
### Algorithms Used
1. **Regression Models:** Multiple Linear Regression, Elastic Net, Gradient Boosting Regressor.
2. **Classification Models:** Logistic Regression, Decision Trees, Naive Bayes, Random Forests, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Neural Networks.
3. **Clustering Algorithms:** K-Means, Mean Shift, Agglomerative Clustering.
4. **Anomaly Detection:** Isolation Forest, Local Outlier Factor (LOF).

### Hyperparameter Tuning
Applied grid search and random search for hyperparameter optimization to improve model performance.

## Evaluation
### Evaluation Metrics
1. **Regression Models:** Root Mean Squared Error (RMSE).
2. **Classification Models:** Precision, Recall, F1-Score, Accuracy, ROC AUC.
3. **Clustering Algorithms:** Silhouette Coefficient, Visual Inspection.
4. **Anomaly Detection Models:** Precision-Recall Curve, ROC Curve, AUC, Confusion Matrix, Classification Report.

### Results and Analysis
Detailed analysis of model performance for each business use case, highlighting key findings and areas for improvement.

## Business Impact and Benefits
### Use Case Outcomes
1. **Financial Budgeting:** Improved financial planning capabilities for customers.
2. **Fraud Detection:** Enhanced fraud prevention and security.
3. **Customer Segmentation:** Insights for personalized marketing campaigns.
4. **Anomaly Detection:** Proactive customer support and early fraud detection.

## Data Privacy and Ethical Concerns
Addressed privacy and ethical concerns by:
- Anonymizing data.
- Ensuring data security.
- Maintaining transparency with customers.

## Collaboration
### Individual Contributions
Each team member's specific contributions to the project.

### Group Dynamics
Overview of group collaboration, communication, and problem-solving strategies.

### Challenges Faced
Key challenges encountered and solutions implemented.

## Conclusion
### Key Achievements
- Developed effective machine learning models for various business needs.
- Provided actionable insights for banking operations.

### Future Work
- Model deployment and continuous improvement.
- Further exploration of advanced algorithms and techniques.

## References
- [Soofi, A., & Awan, A. (2017). Classification Techniques in Machine Learning: Applications and Issues. Journal of Basic & Applied Sciences, 13, 459–465.](https://doi.org/10.6000/1927-5129.2017.13.76)
- [Cheriyan, S., et al. (2018). Intelligent Sales Prediction Using Machine Learning Techniques. IEEE Xplore.](https://doi.org/10.1109/iCCECOME.2018.8659115)
- [Gurnani, M., et al. (2017). Forecasting of sales by using fusion of machine learning techniques. 2017 International Conference on Data Management, Analytics and Innovation (ICDMAI).](https://doi.org/10.1109/icdmai.2017.8073492)
- [Amari, S., & Wu, S. (1999). Improving support vector machine classifiers by modifying kernel functions. Neural Networks, 12(6), 783–789.](https://doi.org/10.1016/s0893-6080(99)00032-5)
