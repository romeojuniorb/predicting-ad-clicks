# 📈 Advertising Dataset Analysis & Ad Click Prediction

## Dataset Source
This project uses the **“Effective Targeting of Advertisements”** dataset from Kaggle.  
[Link to dataset](https://www.kaggle.com/datasets/hiimanshuagarwal/advertising-ef)

---

## 🧰 Project Overview
This notebook explores the relationships between user demographics, behavior metrics, and ad-click behavior. The goal is to uncover patterns and build a predictive model (logistic regression) to classify whether a user will click on an advertisement.

**Key features examined:**
- Age  
- Area Income  
- Daily Time Spent on Site  
- Daily Internet Usage  
- Clicked on Ad (target variable, binary: 0 = No, 1 = Yes)

---

## Analysis Steps
1. **Exploratory Data Analysis (EDA)**  
   - Histograms, boxplots, violin plots to inspect distributions and group differences  
   - Correlation heatmap to examine linear relationships  

2. **Feature Scaling & Preprocessing**  
   - Use `StandardScaler` to standardize numerical features  
   - Train/test split to avoid data leakage  

3. **Model Training & Evaluation**  
   - Logistic Regression classifier  
   - Metrics: accuracy, confusion matrix, classification report  
