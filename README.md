Ola Driver Churn Prediction 🚖


`Problem Statement:` Ola was facing sudden rise in driver atrition rate which was significantally effecting their operational efficiency and recruitment cost.

`Objective:`My objective is to find the pattern between the drivers who had left their job betweeen 2019 to 2021 and  Build and evaluate Machine learning models to predict driver attrition and provide insights for improving retention.

📊 Dataset

The dataset contains driver-related information such as:

Demographics – Age, Gender, City, etc.

Behavioral data – Grade, ratings, etc.

Financial metrics – Income, Total Business Value.

Target variable – Churn (0 = Active, 1 = Churned).


⚙️ Workflow

Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Exploratory Data Analysis (EDA)

Distribution of churned vs non-churned drivers

Correlation heatmaps

Feature importance analysis

Model Building

Logistic Regression

Decision Tree / Random Forest

XGBoost / Gradient Boosting


Model Evaluation

Accuracy, Precision, Recall, F1-score

ROC-AUC curve

Confusion matrix

📈 Results

Best-performing model: (e.g., Random Forest with 87% accuracy, AUC = 0.91)

Top churn predictors: (e.g.Tenure_Days, Quarterly Rating, and Total Business Value, Age, Grade)

Recommendations: Ola should focus retention strategies on **early-career, lower-grade, loan-burdened, and low-earning drivers** through targeted incentives, faster career progression, and stronger onboarding engagement. At the same time, rewarding **high-performing, long-tenured drivers** will maximize business value and build long-term workforce stability.

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost

Environment: Google Colab
