# 💳 Credit Card Fraud Detection using Machine Learning

## 📖 Overview
This project focuses on detecting fraudulent credit card transactions using **Logistic Regression**. The model is trained on a credit card transaction dataset to classify transactions as either fraudulent or legitimate.

## 🛠️ Problem Statement
Credit card fraud is a major concern for financial institutions. The goal of this project is to:
- Build a machine learning model to classify transactions as fraud or non-fraud.
- Analyze the dataset and preprocess it for effective model training.
- Evaluate the model’s performance using accuracy and other relevant metrics.

## ✨ Solution
- **Dataset:** Contains labeled credit card transactions.
- **Data Preprocessing:** 
  - Checked for missing values.
  - Normalized/standardized the features for better model performance.
- **Model Training:**
  - Implemented **Logistic Regression** for fraud classification.
- **Evaluation:** Measured model accuracy and other metrics.

## 📝 Features
- **Fraud Detection Model:** Classifies transactions based on historical data.
- **Performance Metrics:** Evaluated using accuracy and other relevant scores.

## 📊 Libraries and Tools Used
- **Data Processing:** pandas, numpy
- **Machine Learning:** scikit-learn
- **Visualization:** matplotlib, seaborn

## 🚀 How It Works
1. **Input:** The model takes transaction details as input.
2. **Processing:** Features are preprocessed and passed to the trained Logistic Regression model.
3. **Output:** The transaction is classified as either "Fraud" or "Legitimate."

## ⚙️ Output
- The trained **Logistic Regression model** predicts fraudulent transactions.  
- Accuracy and other evaluation metrics are computed:  
  - **Training Accuracy:** 91.99%  
  - **Test Accuracy:** 95.94%

### 🔥 How to Run the Project
1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
2. Run the Jupyter Notebook:  
   ```bash
    jupyter notebook "Credit_Card Fraud Detection.ipynb"
3. Test the model with new transaction data.
