# Fraud Detection Using Machine Learning

## 📌 Problem Statement
Build a machine learning model to detect fraudulent financial transactions using historical transaction data.

## 📊 Dataset
- 6.3M+ transaction records
- Features include transaction type, amount, balance details
- Highly imbalanced fraud dataset

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🔍 Approach
- Data cleaning and validation
- Feature engineering to handle multicollinearity
- Class imbalance handling using class weights
- Model training using Random Forest
- Evaluation using Recall, Precision, ROC-AUC

## 📈 Model Performance
- High fraud recall
- Strong ROC-AUC score
- Low false positive rate

## 🔑 Key Insights
- Fraud mainly occurs in TRANSFER and CASH_OUT transactions
- Large amount transfers with balance inconsistencies are strong fraud indicators

## 🚀 Future Improvements
- XGBoost / LightGBM
- Real-time deployment
- Model monitoring and drift detection
