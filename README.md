# 🏦 Loan Prediction using ANN

## 📋 Introduction

This project focuses on predicting loan approval status using an Artificial Neural Network (ANN). It helps automate the decision-making process in banking systems by analyzing applicant data such as income, credit history, and personal details.

The model improves efficiency, reduces manual effort, and provides accurate predictions for loan approval.

## 📊 Dataset Description

The dataset (loanPrediction.csv) contains applicant details:

- Loan_ID: Unique loan identifier  
- Gender: Male/Female  
- Married: Marital status  
- Dependents: Number of dependents  
- Education: Graduate / Not Graduate  
- Self_Employed: Yes / No  
- ApplicantIncome: Applicant income  
- CoapplicantIncome: Co-applicant income  
- LoanAmount: Loan amount  
- Loan_Amount_Term: Loan duration  
- Credit_History: 0 or 1  
- Property_Area: Urban / Rural / Semiurban  
- Loan_Status: Target variable (Y/N)  

### Data Processing

- Missing values handled  
- Categorical encoding applied  
- Feature scaling done  
- Target variable converted to binary

## 🎯 Project Objective

- Predict loan approval using ANN  
- Automate loan decision process  
- Improve accuracy of predictions  
- Identify key factors affecting approval

## ⚙️ Workflow

1. Data Collection  
2. Data Preprocessing  
3. Exploratory Data Analysis  
4. Model Building (ANN)  
5. Model Training  
6. Model Evaluation  
7. Prediction

## 🧠 Model Details

- Model Type: Binary Classification  
- Algorithm: Artificial Neural Network  

### Architecture
- Input Layer  
- Hidden Layers (ReLU activation)  
- Output Layer (Sigmoid activation)  

### Configuration
- Loss: Binary Crossentropy  
- Optimizer: Adam  
- Metrics: Accuracy

## 📈 Result

The model performs well in predicting loan approval:

- Good accuracy achieved  
- Identifies applicant risk effectively  
- Useful for real-world financial systems

## 📦 Installation & Usage

```bash
git clone https://github.com/RiyaBisht716/Loan-Prediction.git
cd Loan-Prediction
pip install -r requirements.txt
python main.py



---

### 🔹 Replace Future Section

```md
## 🚀 Future Improvements

- Hyperparameter tuning  
- Feature engineering  
- Try advanced models  
- Build web app (Streamlit/Flask)  
- Deploy on cloud  
