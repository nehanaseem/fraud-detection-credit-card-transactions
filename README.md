# Fraud Detection in Credit Card Transactions

## Overview
This project aims to develop a machine learning model to detect fraudulent credit card transactions using a provided dataset. With the increasing volume of transactions, traditional methods are becoming ineffective, necessitating a more robust approach to identify fraudulent activities in real-time.

## Scenario
XPACE TECHNOLOGIES Pvt Ltd is collaborating with a major financial institution that faces challenges in accurately identifying fraudulent credit card transactions. The dataset contains transaction details, and the objective is to build a model that can predict whether a transaction is fraudulent.

## Objectives
1. Understand the patterns that differentiate fraudulent transactions from legitimate ones.
2. Build a predictive model that accurately detects fraud.
3. Provide insights and recommendations for improving the fraud detection process.

## Dataset
The dataset used in this project contains the following columns:
- **Transaction ID**: Unique identifier for each transaction.
- **Customer ID**: Unique identifier for each customer.
- **Transaction Date**: The date and time when the transaction occurred.
- **Transaction Amount**: The amount of money involved in the transaction.
- **Merchant**: The name of the merchant where the transaction took place.
- **Location**: The location of the transaction.
- **Transaction Type**: The type of transaction (e.g., online purchase, in-store purchase, ATM withdrawal).
- **Card Type**: The type of credit card used (e.g., Visa, MasterCard).
- **Is Fraudulent**: A binary indicator (Yes/No) of whether the transaction was fraudulent.

## Tasks
### 1. Data Understanding and Preprocessing
- Perform data exploration to understand the distribution of fraudulent vs. legitimate transactions.
- Handle any missing or inconsistent data.
- Convert categorical variables into numerical representations where necessary (e.g., Merchant, Location, Transaction Type).
- Balance the dataset if it is highly imbalanced (e.g., using techniques like SMOTE).

### 2. Feature Engineering
- Create new features that might help in fraud detection, such as the frequency of transactions by a customer, the average transaction amount, and the time of day of transactions.
- Explore interactions between different features to improve model performance.

### 3. Model Building
- Split the dataset into training and testing sets.
- Experiment with different machine learning algorithms, including Logistic Regression, Random Forest, and Gradient Boosting.
- Tune the model for optimal performance using techniques like cross-validation and grid search.
- Evaluate the model using metrics such as accuracy, precision, recall, F1-score, and area under the ROC curve (AUC-ROC).

## Implementation
The project is implemented in Python using the following libraries:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `seaborn` and `matplotlib`: For data visualization.
- `sklearn`: For machine learning algorithms and model evaluation.
- `imblearn`: For handling imbalanced datasets using SMOTE.

## Usage
Clone the repository to your local machine.
Place the dataset fraud_detection_data.csv in the same directory as the script.
Run the script using Python.

## Results
The model's performance metrics (accuracy, precision, recall, F1 score, AUC-ROC) will be displayed after execution.
Visualizations illustrating the distribution of fraudulent and legitimate transactions will be generated.

## Recommendations
Based on the analysis and model performance, recommendations for improving the fraud detection process can be provided.

## Acknowledgments
Thank you to XPACE TECHNOLOGIES Pvt Ltd for providing the opportunity to work on this project.


## Installation
To run this project, ensure you have the required libraries installed. You can use the following command to install them via pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn imbalanced-learn
```

## Installation

