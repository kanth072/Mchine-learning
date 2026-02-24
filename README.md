📊 Customer Segmentation & Churn Prediction System
🚀 Project Overview

This project implements an advanced Customer Segmentation and Churn Prediction System using machine learning techniques.

The solution:

Segments customers using unsupervised learning

Builds separate predictive models for each segment

Applies hyperparameter tuning

Evaluates models using comprehensive performance metrics

Provides actionable business recommendations

The goal is to improve churn prediction accuracy by modeling customer behavior at a segment level instead of treating all customers the same.

🎯 Objectives

Implement at least 2 clustering algorithms

Build 3+ segment-specific prediction models

Apply hyperparameter tuning

Calculate comprehensive evaluation metrics

Generate meaningful business recommendations

🗂 Dataset

File Used: customer_churn.csv

The dataset contains customer demographic information, service usage details, and churn status.

Target Variable:

Churn (Yes/No)
🧠 Machine Learning Approach
1️⃣ Data Preprocessing

Removed unnecessary identifiers

Label Encoding for categorical variables

Standard Scaling for feature normalization

Target variable converted to binary

2️⃣ Customer Segmentation (Clustering)

Two clustering algorithms were implemented:

🔹 KMeans Clustering

Used to segment customers into 3 clusters

Evaluated using Silhouette Score

🔹 Hierarchical Clustering (Agglomerative)

Used for comparison

Evaluated using Silhouette Score

Final segmentation was selected based on better clustering performance.

3️⃣ Segment-Based Prediction Models

For each customer segment:

Separate training and testing split

Independent model built

Hyperparameter tuning applied

Model Used:

Random Forest Classifier

Hyperparameter Tuning:

Performed using GridSearchCV:

n_estimators

max_depth

min_samples_split

📈 Evaluation Metrics

Each segment model was evaluated using:

Accuracy

Precision

Recall

F1 Score

ROC-AUC Score

This ensures robust and balanced performance analysis.

📊 Sample Output
CUSTOMER SEGMENTS:

Premium Spenders (25%)

Budget Conscious (30%)

Young Professionals (20%)
