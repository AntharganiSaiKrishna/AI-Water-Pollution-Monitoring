🌊💧 AI-Powered Water Pollution Monitoring

AICTE Green AI Internship – Environmental Monitoring & Pollution Control

🌟 Project Overview

This project leverages Artificial Intelligence and Data Science to analyze water pollution data.
The main goal is to understand key water quality parameters (like pH, Dissolved Oxygen, BOD, Turbidity, heavy metals) and build AI models that can predict pollution levels and support smarter environmental monitoring.

📅 Week 1 – Data Understanding & Exploration

Imported Libraries: Pandas, NumPy, Matplotlib, Seaborn

Dataset Loaded: Water_Quality_Dataset.csv

Exploration Steps:

.info() – structure & datatypes

.describe() – statistical summary

.isnull().sum() – check missing values

🔍 Insights:

Missing values detected and analyzed.

Observed ranges of features like pH, Turbidity, Temperature, BOD, DO, Heavy Metals.

Dataset prepared for AI/ML model training.

🧹 Week 2 – Data Preprocessing & Model Training

Missing Values Handled for numeric & categorical features

Categorical Encoding: Location

Feature Scaling: StandardScaler for numeric features

Train-Test Split: 80% training, 20% testing

Models Trained:

Logistic Regression

Decision Tree

Random Forest

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

Feature Importance: Visualized top contributors using Random Forest

Cleaned Dataset Saved: Week2_Cleaned_Dataset.csv

💡 Key Result:

Random Forest Accuracy: ~99% ✅

Top Features: BOD, DO, pH, Turbidity, Heavy Metals

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, scikit-learn

Platform: Jupyter Notebook, GitHub

📁 Dataset

Source: Kaggle – Water Quality Dataset

File Used: Water_Quality_Dataset.csv

Contains water quality measurements and labels (Safe, Moderate, Polluted)

✨ This project is part of the AICTE Green AI Internship in the Environmental Monitoring & Pollution Control domain.
