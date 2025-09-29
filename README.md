# 🚖 Ola Driver Churn Prediction  

## 📝 Problem Statement  
Ola has been experiencing a **sudden rise in driver attrition (churn) between 2019–2021**, significantly impacting operational efficiency, service quality, and recruitment costs.  

## 🎯 Objective  
The goal of this project is to:  
- Analyze **patterns** behind driver churn.  
- Build and evaluate **Machine Learning models** to predict churn.  
- Provide **data-driven insights** for improving driver retention strategies.  

---

## 📊 Dataset  
The dataset contains detailed driver-related information across different aspects:  

- 👤 **Demographics** – Age, Gender, City, etc.  
- ⭐ **Behavioral Data** – Grade, Ratings, etc.  
- 💰 **Financial Metrics** – Income, Total Business Value.  
- 🎯 **Target Variable** – `Churn` (0 = Active, 1 = Churned).  

---

## ⚙️ Workflow  

### 🔧 Data Preprocessing  
- Handling missing values  
- Encoding categorical variables  
- Feature scaling  

### 📊 Exploratory Data Analysis (EDA)  
- Distribution of churned vs. non-churned drivers  
- Correlation heatmaps  
- Feature importance analysis  

### 🤖 Model Building  
- Logistic Regression  
- Decision Tree & Random Forest  
- XGBoost / Gradient Boosting  

### 📈 Model Evaluation  
- Accuracy, Precision, Recall, F1-score  
- ROC-AUC curve  
- Confusion matrix  

---

## 🚀 Results  

- **Best Model:** Random Forest – *87% Accuracy, AUC = 0.91*  
- **Top Churn Predictors:**  
  - 📅 Tenure Days  
  - ⭐ Quarterly Rating  
  - 💰 Total Business Value  
  - 🎓 Grade  
  - 👤 Age  

### ✅ Recommendations  
- **Retain early-career, low-grade, low-earning, and loan-burdened drivers** through:  
  - Targeted incentives  
  - Faster career progression  
  - Stronger onboarding engagement  
- **Reward high-performing, long-tenured drivers** to:  
  - Maximize business value  
  - Build long-term workforce stability  

---

## 🛠️ Tech Stack  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost  
- **Environment:** Google Colab ☁️  

---

## 📌 Future Scope  
- Deploy the model as a **Flask/Django web app** for real-time predictions.  
- Integrate **live driver data streams** for proactive churn detection.  
- Experiment with **Deep Learning models** for advanced prediction.  

---

## 👨‍💻 Author  
**Aymash Ansari** 
