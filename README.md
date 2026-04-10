📌 Loan Prediction using ANN

This project aims to predict loan approval status using an Artificial Neural Network (ANN) based on applicant demographic and financial information. The model is trained on a structured dataset containing real-world loan application features.

📊 Dataset Description

The dataset (loanPrediction.csv) consists of 13 features related to loan applicants:

Loan_ID – Unique identifier for each applicant
Gender – Male/Female
Married – Marital status
Dependents – Number of dependents
Education – Graduate / Not Graduate
Self_Employed – Employment status
ApplicantIncome – Income of the applicant
CoapplicantIncome – Income of co-applicant
LoanAmount – Requested loan amount
Loan_Amount_Term – Loan repayment term
Credit_History – Credit history (0 or 1)
Property_Area – Urban / Rural / Semiurban
Loan_Status – Target variable (Y = Approved, N = Not Approved)
🎯 Project Objective

The goal is to build a classification model that can:

Predict whether a loan will be approved (Loan_Status)
Identify key factors influencing loan approval
Assist financial institutions in decision-making
⚙️ Workflow
Data Preprocessing
Handling missing values
Encoding categorical variables
Feature scaling
Exploratory Data Analysis (EDA)
Understanding distributions
Identifying correlations
Model Building
Artificial Neural Network (ANN)
Input layer → Hidden layers → Output layer
Training
Loss Function: Binary Crossentropy
Optimizer: Adam
Evaluation
Accuracy
Confusion Matrix
Precision & Recall
🧠 Model Details
Type: Binary Classification
Algorithm: Artificial Neural Network (ANN)
Activation Functions: ReLU (hidden layers), Sigmoid (output layer)
📈 Results

The ANN model successfully learns patterns from applicant data and provides reliable predictions for loan approval, with strong performance based on evaluation metrics.

🛠️ Installation & Usage
# Clone the repository
git clone https://github.com/your-username/loan-prediction-ann.git

# Move into project directory
cd loan-prediction-ann

# Install dependencies
pip install -r requirements.txt

# Run the model
python main.py
📌 Future Improvements
Hyperparameter tuning
Feature engineering
Try other models (Random Forest, XGBoost)
Deploy as a web app
