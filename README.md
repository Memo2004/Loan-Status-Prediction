# Loan Status Prediction 🏦📊

A machine learning project to predict whether a loan application will be approved or not based on applicant data.

## 📁 Project Structure

Loan-Status-Prediction/
├── dataset/                # Contains the CSV file used for training  
├── notebooks/              # Jupyter notebooks for EDA, preprocessing, and modeling   
└── README.md               # Project overview and documentation

## 📌 Objective

The goal of this project is to build a machine learning model that predicts the **Loan Status** (`Y` or `N`) using various applicant features such as income, credit history, loan amount, etc.  
This can help financial institutions to automate and speed up the loan approval process.

## 📂 Dataset

- **Source**: [Kaggle - Loan Status Prediction Dataset](https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction)  
- **Size**: ~600 rows  
- **Features**:
  - `Gender`, `Married`, `Education`, `Self_Employed`
  - `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`
  - `Credit_History`, `Property_Area`, `Loan_Status`

## 📊 Exploratory Data Analysis (EDA)

- Handled missing values and data types  
- Analyzed distributions and relationships between features  
- Found that **Credit_History** and **LoanAmount** were strong indicators of loan approval

## 🧠 Models Used

- Logistic Regression  
- Bagging
- Gradient Boosting 
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- XGB
- Decision Tree 

### ✅ Evaluation Metrics

- Accuracy  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)

## 🚀 Results

| Model                        | Accuracy (%) |
|------------------------------|--------------|
| Logistic Regression          | 85.80        |
| Bagging                      | 86.45        |
| Gradient Boosting            | 85.80        |
| Random Forest                | 85.80        |
| Support Vector Machine (SVM) | 87.09        |
| K-Nearest Neighbors (KNN)    | 85.80        |
| XGB                          | 85.80        |
| Decision Tree                | 80.64        |

## 🛠️ How to Run

1. Clone the repo:

```bash
git clone https://github.com/Memo2004/Loan-Status-Prediction.git
cd Loan-Status-Prediction
