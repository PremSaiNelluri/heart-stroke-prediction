# 🩺 Heart Stroke Prediction using Hybrid ML Models

## 📌 Project Overview
This project aims to predict the likelihood of a **heart stroke** using **hybrid machine learning models**.  
By combining multiple ML algorithms, the system enhances prediction accuracy compared to traditional single-model approaches.  
The model is designed to help in **early diagnosis and preventive healthcare** by analyzing patient health data.

---

## 📊 Dataset
- **Source:** [dataset.zip provided]  
- **Features include:**
  - Age  
  - Gender  
  - Hypertension  
  - Heart disease history  
  - Work type & Residence type  
  - Average glucose level  
  - Body Mass Index (BMI)  
  - Smoking status  

- **Target Variable:** `stroke` (0 = No Stroke, 1 = Stroke)

---

## ⚙️ Technologies Used
- **Python 3.9+**
- **Jupyter Notebook**
- **Libraries:**
  - pandas, numpy
  - matplotlib, seaborn (EDA & visualization)
  - scikit-learn
  - xgboost / lightgbm
  - ensemble methods (Random Forest, Voting Classifier)

---

## 🧪 Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling & normalization

2. **Exploratory Data Analysis (EDA)**
   - Identifying patterns, correlations, and risk factors
   - Visualization of stroke vs non-stroke cases

3. **Model Development**
   - Trained multiple ML models:
     - Logistic Regression
     - Random Forest
     - XGBoost
   - Hybrid approach:
     - **Voting Classifier / Stacking Ensemble**

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC for stroke prediction

---

## 📈 Results
- The **hybrid ML model** outperformed single models.  
- Achieved higher **prediction accuracy and robustness**.  
- Identified critical features: age, glucose level, BMI, hypertension, smoking status.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/heart-stroke-prediction.git
