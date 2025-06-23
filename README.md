# Employee Attrition Prediction

This project predicts whether an employee is likely to leave a company using HR analytics data. It uses machine learning models (Random Forest & Logistic Regression) and explainable AI (SHAP) to uncover key factors behind employee attrition.

---

## 📂 Dataset

- **Source**: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **File**: `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- **Records**: 1470 employees
- **Target column**: `Attrition` (`Yes` / `No`)

---

## 🔍 Features

| Type           | Examples                          |
|----------------|-----------------------------------|
| Demographics   | Age, Gender, MaritalStatus        |
| Job Info       | JobRole, MonthlyIncome, OverTime  |
| Satisfaction   | JobSatisfaction, WorkLifeBalance  |
| Tenure         | YearsAtCompany, TotalWorkingYears |

---

## 🚀 Project Structure
- ├── attrition_model.py # Main script with model and SHAP explanation
- ├── WA_Fn-UseC_-HR-Employee-Attrition.csv # Dataset (not included - download separately)
- ├── README.md
- ├── requirements.txt


---

## ✅ Key Components

### 📊 1. Exploratory Data Analysis (EDA)
- Visualize attrition distribution
- Explore feature relationships (income, overtime, satisfaction)

### 🤖 2. Model Training
- Logistic Regression
- Random Forest Classifier

### 🧠 3. Explainable AI with SHAP
- Summary plots to highlight global feature importance
- Force plots to explain individual predictions

### 📌 4. HR Actionable Insights
- Reduce overtime, improve job satisfaction, and target early leavers

---

## 🛠️ How to Use

### ▶️ Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/employee-attrition-prediction.git
cd employee-attrition-prediction

# Install dependencies
pip install -r requirements.txt

# Run the script
python attrition_model.py
