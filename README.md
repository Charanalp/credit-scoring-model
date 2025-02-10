Credit Scoring Model

📄 Project Description

The Credit Scoring Model is a machine learning project aimed at predicting the creditworthiness of individuals based on historical financial data. This model helps financial institutions assess potential risks before approving credit applications. Using classification algorithms, the model predicts whether a client is likely to repay a loan, enabling data-driven decision-making.

🚀 Features

Predicts credit risk levels for individuals.

Handles missing values and performs data preprocessing.

Encodes categorical data for model compatibility.

Scales features for improved model performance.

Provides performance metrics including accuracy, precision, recall, F1-score, and confusion matrix.

🛠️ Technologies Used

Python

Pandas - for data manipulation and analysis

NumPy - for numerical computations

Scikit-learn - for machine learning algorithms and performance evaluation

Matplotlib & Seaborn - for data visualization

Google Colab - for running the Jupyter notebook environment

⚙️ How to Run

Clone the Repository:

git clone https://github.com/Charanalp/credit-scoring-model.git
cd credit-scoring-model

Upload the Dataset:

Download the dataset from Kaggle Dataset - Credit Risk Dataset.

Place train.xlsx and test.xlsx files in the project directory.

Open Google Colab:

Upload the Credit_Scoring_Model.ipynb file.

Run the notebook cell by cell.

Install Required Libraries (if needed):

!pip install pandas numpy scikit-learn matplotlib seaborn

📊 Dataset Source

Kaggle: Credit Risk Dataset

Description: The dataset includes details like account information, investment totals, client demographics, loan quality, and repayment modes.

📈 Results & Performance Metrics

Accuracy: 98.40%

📋 Classification Report:

               precision    recall  f1-score   support

           B       0.02      0.05      0.03        19
          DF       0.00      0.00      0.00         4
           G       0.99      0.99      0.99      4286
          SS       0.00      0.00      0.00         1

    accuracy                           0.98      4310
   macro avg       0.25      0.26      0.26      4310
weighted avg       0.99      0.98      0.99      4310

🔍 Confusion Matrix:

[[   1    0   18    0]
 [   0    0    4    0]
 [  46    0 4240    0]
 [   0    0    1    0]]

🤝 Contributing

Pull requests are welcome. For significant changes, please open an issue first to discuss what you would like to change.

📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

