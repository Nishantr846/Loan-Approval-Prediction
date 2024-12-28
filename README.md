## Loan Approval Prediction System

This project implements a Loan Approval Prediction System using a Support Vector Machine (SVM) model. The system predicts whether a loan application will be approved or not based on the applicant's details. The model is trained on a dataset with features such as income, education, credit history, and property area.

## Features
### Input Features:
Gender
Marital Status
Number of Dependents
Education Level
Employment Status
Applicant Income
Co-applicant Income
Loan Amount
Loan Term
Credit History
Property Area

### Output:
Loan Approved or Loan Not Approved
Technologies Used
Programming Language: Python
Libraries:
pandas for data handling
numpy for numerical operations
scikit-learn for machine learning models
StandardScaler for feature scaling
SVM for prediction

## Getting Started

### Prerequisites
Make sure you have Python 3.x installed along with the required libraries. Install the dependencies using:

pip install pandas numpy scikit-learn
Dataset
Download or use your own loan dataset. Ensure it has the required columns such as Loan_Status, Loan_ID, and others.
Place the dataset in the project directory.
Update the file path in the script to point to your dataset.
Running the Project

Clone the repository:

git clone https://github.com/your-username/loan-approval-prediction.git
cd loan-approval-prediction
Update the example_data in the script to match your input data.

Run the script:


python loan_approval_prediction.py

he output will be either:

Loan Approved
Loan Not Approved


## Project Workflow
Data Preprocessing:

Missing values are dropped.
Categorical columns are encoded into numerical values.
Feature Scaling:

Input features are standardized using StandardScaler.
Model Training:

SVM model is trained using the training dataset.
Prediction:

User inputs are transformed and passed to the model for prediction.
### Example Input

example_data = [1, 0, 1, 0, 2, 4000, 1500, 128, 360, 1, 1]
Explanation of Input
Feature	Value Description
Gender	1: Male, 0: Female
Married	1: Yes, 0: No
Dependents	0, 1, 2, 4
Education	1: Graduate, 0: Not Graduate
Self_Employed	1: Yes, 0: No
ApplicantIncome	Income of the applicant in numbers
CoapplicantIncome	Income of the co-applicant in numbers
LoanAmount	Loan amount in thousands
Loan_Amount_Term	Loan term in months
Credit_History	1: Good, 0: Bad
Property_Area	0: Rural, 1: Semiurban, 2: Urban
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Feel free to submit a pull request or open an issue if you find bugs or want to add features!

Contact
For any queries, please reach out to:

Name: Nishant
Email: nishantr846@gmail.com
GitHub: Nishantr846
