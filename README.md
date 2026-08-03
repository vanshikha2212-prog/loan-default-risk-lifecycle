# 🏦 Loan Default Risk Prediction

An end-to-end Machine Learning project that predicts whether a loan application is likely to be approved or rejected based on applicant information. This project follows the complete data science lifecycle—from data preprocessing and exploratory data analysis to model building, evaluation, and interpretation.

---

## 📌 Project Objective

Financial institutions receive thousands of loan applications every day. Incorrect lending decisions can either:

- Increase financial losses by approving risky applicants.
- Reduce business opportunities by rejecting eligible applicants.

The objective of this project is to build and compare multiple machine learning models that can predict loan approval status using applicant information.

---

## 📊 Dataset

The dataset contains information about loan applicants, including:

- Gender
- Marital Status
- Education
- Self Employment
- Number of Dependents
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area

**Target Variable**

- Loan_Status
    - 1 → Approved
    - 0 → Rejected

---

# 🛠 Project Workflow

### 1. Data Cleaning

- Removed unnecessary columns
- Handled missing values
- Encoded categorical variables
- Created Total Income feature

---

### 2. Exploratory Data Analysis

Performed:

- Distribution Analysis
- Correlation Analysis
- Feature Importance Analysis
- Class Distribution Analysis

---

### 3. Data Preprocessing

- Train-Test Split
- Feature Scaling (Logistic Regression)
- Feature Encoding

---

### 4. Models Implemented

### Logistic Regression

A simple and interpretable linear classification model used as the baseline.

### Decision Tree

A rule-based model capable of learning non-linear decision boundaries.

### Random Forest

An ensemble learning method combining multiple decision trees to improve robustness and reduce overfitting.

---

# 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **78.86%** |
| Decision Tree | 70.73% |
| Random Forest | **78.86%** |

---

# 📉 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score
- ROC Curve
- AUC Score

**Best ROC-AUC Score:** **0.74**

---

# 🔍 Key Insights

- Credit History was the most important predictor of loan approval.
- Total Income and Applicant Income also contributed significantly.
- Logistic Regression performed as well as Random Forest on this dataset while remaining more interpretable.
- Decision Tree achieved lower performance due to overfitting and poorer generalization.

---

# 📂 Project Structure

```
loan-default-risk-lifecycle/
│
├── data/
│   └── raw/
│       └── train.csv
│
├── notebooks/
│   └── loan-prediction-analysis.ipynb
│
├── scripts/
│   └── simple_analysis.py
│
├── .gitignore
└── README.md
```

---

# 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# 🚀 Future Improvements

Some potential improvements include:

- Hyperparameter tuning using GridSearchCV
- XGBoost and LightGBM models
- Cross Validation
- Feature Engineering
- Probability Threshold Optimization
- Model Deployment using Flask or FastAPI
- Interactive dashboard using Streamlit

---

# 📚 What I Learned

Through this project, I gained practical experience with:

- Data preprocessing
- Feature engineering
- Exploratory data analysis
- Logistic Regression
- Decision Trees
- Random Forests
- Model evaluation
- ROC-AUC analysis
- Feature importance interpretation
- End-to-end machine learning workflow

---

## 👩‍💻 Author

**Vanshikha Kandregula**

B.Sc. Applied Statistics & Data Science  
Symbiosis Statistical Institute

GitHub: https://github.com/vanshikha2212-prog

---
