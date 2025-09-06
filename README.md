# 🏡 House Pricing Prediction with KNN and XGBoost

This project predicts house prices using **Machine Learning models**. It applies both **K-Nearest Neighbors (KNN)** and **XGBoost** to build and compare predictive models.  

---

## 📌 Project Overview
- **Objective:** Estimate house prices based on features such as area, number of rooms, location, and year built.  
- **Models Used:**
  - **K-Nearest Neighbors (KNN):** A simple, distance-based regression model.  
  - **XGBoost:** A powerful gradient boosting algorithm that handles complex feature interactions.  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - Data Handling → `pandas`, `numpy`  
  - Visualization → `matplotlib`, `seaborn`  
  - Machine Learning → `scikit-learn`, `xgboost`  
- **Environment:** Jupyter Notebook / VS Code  

---

## 🔍 Workflow
1. **Data Collection:** Train/test datasets with house features.  
2. **Data Preprocessing:**
   - Handle missing values  
   - Encode categorical variables  
   - Normalize/scale numerical features  
3. **Exploratory Data Analysis (EDA):** Visualize distributions, correlations, and outliers.  
4. **Model Training:**
   - Train KNN and XGBoost models  
   - Hyperparameter tuning  
5. **Evaluation:**
   - Compare models using RMSE, MAE, and R² score  

---

## 📊 Results
- **KNN:** Works well with normalized data but sensitive to outliers.  
- **XGBoost:** Provides higher accuracy and generalization on unseen data.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Ratikanta029/House-Pricing-with-KNN-and-XGBoost.git
   cd House-Pricing-with-KNN-and-XGBoost
