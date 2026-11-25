# 💳 Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview

Credit Card Fraud Detection is a Machine Learning project designed to identify fraudulent credit card transactions and distinguish them from genuine transactions.

This project uses the Credit Card Fraud Detection dataset to perform data analysis, preprocessing, visualization, and model training. Three machine learning algorithms are implemented and compared to evaluate their performance in detecting fraudulent transactions.

## 🎯 Project Objectives

- Analyze credit card transaction data.
- Identify patterns in fraudulent and genuine transactions.
- Perform Exploratory Data Analysis (EDA).
- Prepare and scale data for machine learning.
- Train and evaluate multiple classification models.
- Compare model performance using different evaluation metrics.

## 📊 Dataset Information

- **Dataset:** Credit Card Fraud Detection (ULB)
- **Total Records:** 284,807
- **Total Features:** 30
- **Total Columns:** 31
- **Target Variable:** Class
- **Class 0:** Genuine Transaction
- **Class 1:** Fraudulent Transaction

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook / Google Colab

## ⚙️ Project Workflow

1. Dataset Downloading and Loading
2. Data Understanding and Quality Checking
3. Exploratory Data Analysis (EDA)
4. Fraud vs Genuine Transaction Analysis
5. Transaction Amount Analysis
6. Correlation Analysis and Heatmaps
7. Feature Distribution Analysis
8. Train-Test Splitting (80:20)
9. Feature Scaling using StandardScaler
10. Machine Learning Model Training
11. Model Evaluation and Comparison
12. Best Model Selection

## 🤖 Machine Learning Algorithms

Three classification algorithms were implemented:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **XGBoost Classifier**

## 📈 Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 97.55% | 6.10% | 91.84% | 11.44% |
| Random Forest | 99.95% | 96.05% | 74.49% | 83.91% |
| XGBoost | 99.96% | 93.98% | 79.59% | 86.19% |

## 🏆 Best Model: XGBoost

Based on the model comparison, XGBoost achieved the highest F1-score of **86.19%**, with an accuracy of **99.96%**.

It provided the best overall balance between precision and recall among the three evaluated models.

## 📊 Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

## 💡 Key Learnings

- Understanding real-world financial datasets.
- Performing Exploratory Data Analysis.
- Handling highly imbalanced classification data.
- Applying feature scaling.
- Training multiple machine learning algorithms.
- Comparing classification models using evaluation metrics.
- Understanding the importance of precision, recall, and F1-score in fraud detection.

## 🚀 Future Improvements

- Experiment with advanced class-imbalance handling techniques.
- Perform hyperparameter tuning.
- Explore additional machine learning algorithms.
- Develop an interactive fraud detection dashboard.
- Build a simple web application for transaction prediction.

## 👨‍💻 Author

**Sujal Teli**

GitHub: [@sujalteli](https://github.com/sujalteli)

LinkedIn: [Sujal Teli](https://linkedin.com/in/sujal-teli/)

---

⭐ If you find this project interesting, consider giving this repository a star!
