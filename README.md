# Car Claim Insurance Data Analysis

**Predicting whether a policyholder will file a car insurance claim in the next 6 months using machine learning models.**

---

## Problem Statement
The goal of this project is to develop a predictive model that forecasts whether a policyholder will file a claim within the next 6 months. This is a **binary classification problem** that can help insurance companies improve risk assessment and decision-making.

---

## Dataset
- **Name:** Car Insurance Claim Prediction  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification)  
- **Size:** 58,592 rows × 44 columns  
- **Target Variable:** `is_claim` (Boolean: whether a claim was filed in the next 6 months)  
- **Features:** Policy tenure, age of the car, age of the car owner, city population density, make and model of the car, power, engine type, and more.

---

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn, XGBoost  
- Jupyter Notebook

---

## Methodology
1. **Exploratory Data Analysis (EDA):**  
   - Analyzed distributions, missing values, outliers, and correlations between features.  
   - Identified key patterns that influence insurance claims.

2. **Data Preprocessing:**  
   - Handled missing values and encoded categorical variables.  
   - Addressed outliers and normalized numerical features.  
   - Performed feature selection using correlation analysis and PCA.

3. **Modeling:**  
   - Trained and evaluated multiple machine learning models (Random Forest, XGBoost).  
   - Fine-tuned hyperparameters to optimize predictive performance.  
   - Evaluated models using accuracy, confusion matrix, and other relevant metrics.

4. **Results & Insights:**  
   - Achieved **96% prediction accuracy** on the test set.  
   - Key features impacting claim probability include age of the car, policy tenure, and car power.  
   - The model can help insurers identify high-risk policyholders and optimize claim management.



## 📸 Sample Visualizations
*(Add screenshots or plots from your notebook here)*  
