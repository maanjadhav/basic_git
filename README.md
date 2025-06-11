# 🕵️‍♂️ Fraud Detection - Exploratory Data Analysis (EDA)

This project performs an Exploratory Data Analysis (EDA) on a credit card fraud detection dataset. The main objective is to understand the structure, distribution, and patterns in the data to support building machine learning models for detecting fraudulent transactions.

---

## 📁 Dataset

The dataset used in this project is the **[Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)** available on Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders.

- **Rows:** 284,807 transactions  
- **Features:** 30 anonymized features (`V1` to `V28`), `Time`, `Amount`, and the target label `Class`  
- **Target Variable:** `Class`  
  - `0`: Non-fraud  
  - `1`: Fraud  

---

## 🔍 EDA Objectives

- Analyze class distribution (Imbalance)
- Examine distributions of key features
- Visualize correlations among features
- Detect outliers and anomalies
- Explore transaction patterns over time and amount

---

## 📊 Key Visualizations

- Class imbalance pie chart / bar plot  
- Histograms and boxplots of `Amount` and `Time`  
- Correlation heatmap  
- Pairplots of selected features  
- Time-series visualization of fraud transactions  

---

## 🛠️ Tools and Libraries

- Python (Google Colab)
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn (for preprocessing)

---

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fraud-detection-eda.git
   cd fraud-detection-eda
