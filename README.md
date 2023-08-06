# Streamlit_Bank_Loan_Prediction-master

![Screenshot 2023-08-06 131339](https://github.com/Kunal453/Streamlit_Bank_Loan_Prediction-master/assets/103109790/0c2bda32-5fb9-4a4c-a125-7269f8b7dace)


## Description

This project aims to build a web application using Streamlit to predict whether a bank loan application will be approved or rejected based on various features such as income, credit score, loan amount, etc. 
The application is designed to be user-friendly, allowing users to input their details and receive an instant prediction.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)

## Installation
1. Clone the repository:
bash
</br>git clone https://github.com/Kunal453/Streamlit_Bank_Loan_Prediction-master.git</br>
</br>cd Streamlit_Bank_Loan_Prediction-master</br>

2. Install required dependencies:<br/>
<br>pip install -r requirements.txt</br>

## Usage
<br>To run the Streamlit application, execute the following command in your terminal:</br>
<br>python -m streamlit run Bank_Loan_Prediction.py</br>
<br>The application will start, and you can access it by opening your web browser and navigating to http://localhost:8501.</br>

## Data Prepration.
<br>The dataset for the Loan Prediction Model contains two CSV files: train.csv and test.csv.</br><br>The train.csv file has 614 rows and 13 columns, while the test.csv file has 367 rows and 12 columns.<br>The objective of the model is to predict whether a loan application will be approved or not, based on several input variables.</br>
<br> Feature Description: The features (variables) in the dataset are as follows:</br>
<br>• Loan_ID: Unique identifier for the loan application</br>
<br>• Gender: Gender of the applicant (Male/Female)</br>
<br>• Married: Marital status of the applicant (Yes/No)</br>
<br>• Dependents: Number of dependents the applicant has (0/1/2/3+)</br>
<br>• Education: Education level of the applicant (Graduate/Not Graduate)</br>
<br>• Self_Employed: Whether the applicant is self-employed or not (Yes/No)</br>
<br>• ApplicantIncome: Income of the applicant</br>
<br>• CoapplicantIncome: Income of the co-applicant</br>
<br>• LoanAmount: Loan amount requested by the applicant</br>
<br>• Loan_Amount_Term: Term of the loan in months</br>
<br>• Credit_History: Credit history of the applicant (1=good credit history, 0=bad
credit history)</br>
<br>• Property_Area: Type of property in which the loan is being applied for
(Urban/Semiurban/Rural)</br>
<br>• Loan_Status: Whether the loan was approved or not (Y/N)</br>

## Model
<br>we use four ML algorithm to testing our model to find the  best accuracy score to prdeict the loan.</br><br>There are Logistic Regression, Decision Trees, Random Forest, Support Vector Machines</br>

<br>Here we used the following commands to execute our model:</br>
<br>from sklearn.tree import DecisionTreeClassifier</br>
<br>from sklearn.svm import SVC</br>
<br>from sklearn.linear_model import LogisticRegression</br>
<br>from sklearn.ensemble import RandomForestClassifier</br>

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
## Result
<br>![image](https://github.com/Kunal453/Streamlit_Bank_Loan_Prediction-master/assets/103109790/7c3e1b04-7055-4ddf-9610-15a047dcf88e)</br>
<br>![image](https://github.com/Kunal453/Streamlit_Bank_Loan_Prediction-master/assets/103109790/f122f281-517e-49c9-83d4-afdf593e1354)</br>
<br>![image](https://github.com/Kunal453/Streamlit_Bank_Loan_Prediction-master/assets/103109790/467b1e35-6632-493d-9c74-faa7ed3c580b)
</br>

