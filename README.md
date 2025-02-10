# credit-scoring-model
Credit Scoring Model using Machine Learning | Predicting creditworthiness based on financial data with classification algorithms, feature scaling, and performance evaluation. Built with Python, scikit-learn, and pandas
# Credit Scoring Model

This project focuses on developing a **Credit Scoring Model** to predict the creditworthiness of individuals based on historical financial data. The model uses machine learning classification algorithms to analyze customer data and assess the risk of default.

## 🚀 Features
- Data Preprocessing and Cleaning
- Handling Missing Values
- Encoding Categorical Variables
- Feature Scaling using StandardScaler
- Model Training with Random Forest Classifier
- Performance Evaluation (Accuracy, Confusion Matrix, Classification Report)

## 📊 Dataset
The dataset contains financial information such as:
- **ACC_NO:** Account Number  
- **INVESTMENT_TOTAL:** Total Investment  
- **ACCCURRENTBALANCE:** Current Account Balance  
- **INF_MARITAL_STATUS:** Marital Status  
- **INF_GENDER:** Gender  
- **INSTALL_SIZE:** Installment Size  
- **DUE_PAYMENT:** Due Payment Amount  
- **COMPENSATION_CHARGED:** Compensation Charged  
- **CLIENT_TYPE:** Type of Client  
- **QUALITY_OF_LOAN:** Quality Rating of Loan  
- **REPAY_MODE:** Mode of Repayment (Target Variable)  

## ⚡ Installation
Clone the repository:
```bash
git clone https://github.com/your_github_username/credit-scoring-model.git
cd credit-scoring-model
**
📝 Requirements**
Python 3.x
pandas
scikit-learn
matplotlib
seaborn
imbalanced-learn (for handling imbalanced data)


Install the dependencies:
pip install pandas scikit-learn matplotlib seaborn imbalanced-learn

🚀 Running the Model

jupyter notebook Credit_Scoring_Model.ipynb
Or open it directly in Google Colab.


📈 Model Performance
Accuracy: 98.4%
The model is currently biased towards class 'G' due to class imbalance. Improvements with SMOTE and class weighting are recommended.
🤝 Contributing
Feel free to fork this repository, submit pull requests, and suggest improvements.

📧 Contact
For queries, reach out to:

Charan - vtu23416@veltech.edu.in


