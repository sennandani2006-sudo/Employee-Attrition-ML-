# Employee Attrition Prediction using Machine Learning

This project focuses on predicting employee attrition using machine learning techniques.  
The goal is to analyze employee data, perform preprocessing, visualize insights, and build a predictive model.

---

## 📊 Dataset
- **Name:** IBM HR Analytics Employee Attrition Dataset  
- **File:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- **Description:** Contains employee demographic, job-related, and satisfaction-related features.

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:
- Converted target variable `Attrition` to binary format  
  - Yes → 1  
  - No → 0
- Removed irrelevant columns:
  - EmployeeCount
  - EmployeeNumber
  - Over18
  - StandardHours
- Encoded categorical variables using One-Hot Encoding
- Split data into training and testing sets (80% / 20%)
- Applied feature scaling using StandardScaler

---

## 📈 Exploratory Data Analysis (EDA)
Key visualizations include:
- Employee Attrition count
- Age distribution
- Monthly income distribution
- Attrition by department and gender

These plots help in understanding patterns and trends related to employee attrition.

---

## 🤖 Model Building
- **Model Used:** Logistic Regression
- Logistic Regression was chosen because it is effective for binary classification problems.

---

## 📉 Model Evaluation
The model was evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-score)

### Accuracy Achieved
- Approximately **85%** accuracy on the test dataset.

---

## 🔍 Key Observations
- Majority of employees do not leave the organization.
- Higher attrition observed among employees with:
  - Lower monthly income
  - Lower job satisfaction
  - Certain job roles and departments
- Class imbalance exists in the target variable.

---

## 🚀 Suggestions for Improvement
- Handle class imbalance using techniques like SMOTE
- Try advanced models such as Random Forest or XGBoost
- Perform hyperparameter tuning
- Analyze feature importance
- Deploy the model using a web framework like Streamlit

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## ▶️ How to Run the Project
1. Install required libraries:
   ```bash
   pip install -r requirements.txt
