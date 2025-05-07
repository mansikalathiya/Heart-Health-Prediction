# Heart Disease Prediction using Machine Learning

This project aims to predict heart disease using machine learning algorithms based on patient medical data. The predictive model is built to assist medical professionals in diagnosing the risk of heart disease and improve early detection outcomes.

## 📊 Dataset Information
- **Rows**: 303  
- **Columns**: 14 (including the target label `Target`)  
- **Data Types**: A mix of categorical and continuous variables  
- **Target Variable**: `Target` (1 = Disease, 0 = No Disease)

## 🧹 Data Cleansing
- Only one column contained null values.
- Two rows had missing data and were removed using the `dropna()` function, as the loss was minimal and did not affect model performance.

## 📈 Data Visualization
- A **correlation matrix** was used to identify the most influential features.
- **Age** was found to be most strongly correlated with the presence of heart disease.
- Graphs and plots were generated to show class distribution and feature importance for the label (`Target`), helping to understand the imbalance and trends in the dataset.

## 🔍 Methodology
To interpret and resolve the medical objectives, multiple data science techniques and machine learning algorithms were implemented, including:

- **Random Forest**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Logistic Regression**

Each model was trained using the preprocessed dataset. The goal was to determine the most accurate algorithm for predicting heart disease.

## ✅ Results
- **Cross-validation** was performed to ensure robustness and avoid overfitting.
- All models showed relatively similar performance with slight variation.
- **Logistic Regression** outperformed other models in terms of accuracy and consistency, making it the preferred choice for this prediction task.

## 🛠 Installation Guide

1. Install **Anaconda Distribution**  
2. Launch **Jupyter Notebook**  
3. Clone or download this repository:
   ```bash
   git clone https://github.com/mansikalathiya/Heart-Health-Prediction.git
