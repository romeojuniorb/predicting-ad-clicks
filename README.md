# Advertising Dataset Analysis & Ad Click Prediction

## Dataset Source
This project uses the **“Effective Targeting of Advertisements”** dataset from Kaggle.  
[Link to dataset](https://www.kaggle.com/datasets/hiimanshuagarwal/advertising-ef)

---

## Project Overview
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
  
The analysis of the Advertising Effectiveness dataset highlights several key factors influencing user ad-click behavior:

**Age:** Older users are more likely to click on ads, while younger users are less responsive.

**Area Income:** Users from higher-income areas tend to ignore ads, whereas those from lower- to middle-income areas engage more frequently.

**Daily Internet Usage & Time Spent on Site:** Heavy internet users and those who spend more time on the site are less likely to click on ads, suggesting ad fatigue. In contrast, lighter users with shorter browsing sessions are more responsive.

Overall, ad targeting strategies should prioritize older, lower- to middle-income users with moderate online activity, as they represent the most engaged segment. For high-income or heavy internet users, advertisers may need to adopt more tailored and premium marketing approaches to capture attention effectively.
