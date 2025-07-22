# Loan Approval Prediction using Random Forest

## 📌 Project Overview
This project predicts whether a loan application will be approved based on applicant details using machine learning techniques. The goal is to develop a robust, explainable, and balanced classification model that can assist in loan approval decisions.

---

## ✅ Key Highlights
- **Data Cleaning**: Handled missing values using median and mode strategies.
- **Feature Engineering**: Added financial ratios such as `Total Income`, `Loan to Income Ratio`, `EMI`, and `Income per Person` to enhance predictive power.
- **Class Imbalance Handling**: Used `class_weight='balanced'` to improve recall on the minority class (loan not approved).
- **Model Building**: Applied `RandomForestClassifier` with Stratified K-Fold Cross Validation and `GridSearchCV` for hyperparameter tuning.
- **Business Insights**: Identified top influencing factors like `Credit History`, `Total Income`, and `Loan Income Ratio`.

---

## 📊 Model Performance
- **Accuracy**: ~83%
- **Recall (Loan Not Approved)**: ~74%
- **Outcome**: Balanced model performance suitable for minimizing risk in loan approvals.

---

## 📁 Repository Structure
├── Loan_Approval_Prediction.ipynb # Main Notebook

├── train.csv # Dataset

└── README.md # Project Summary


---

## 📈 Business Insights
- The model focuses on reducing false approvals by improving recall for loan rejections.
- Provides clear, interpretable insights on key drivers affecting loan decisions.

---

## 🚀 How to Run
1. Clone the repository
2. Upload `train.csv` into your working directory or Colab
3. Open and run `Loan_Approval_Prediction.ipynb` step by step

---

## 📌 Conclusion
This project demonstrates a full-cycle data science pipeline from data preprocessing to model deployment insights, making it a portfolio-ready example for practical business applications.

