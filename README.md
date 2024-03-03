## Project Title
Loan Approval Prediction


## Problem Description 
Loan approval prediction refers to the use of machine learning techniques to predict the likelihood of a loan application being approved or denied by banks and financial institutions. By using advanced algorithms and predictive models, banks can streamline their loan approval processes and make informed decisions for the benefit of both lenders and borrowers.

## Objective 
Create a model that can accurately predict whether a loan request will be approved or denied, based on the details provided by the applicant. The model should have high accuracy in determining loan approval outcomes.

## Dataset Description 

- Variable Name 	Description 	Sample Data
- Loan_ID 	Loan reference number
- (unique ID) 	LP001002; LP001003; ...
- Gender 	Applicant gender
- (Male or Female) 	Male; Female
- Married 	Applicant marital status
- (Married or not married) 	Married; Not Married
- Dependents 	Number of family members 	0; 1; 2; 3+
- Education 	Applicant education/qualification
- (graduate or not graduate) 	Graduate; Under Graduate
- Self_Employed 	Applicant employment status
- (yes for self-employed, no for employed/others) 	Yes; No
- ApplicantIncome 	Applicant's monthly salary/income 	5849; 4583; ...
- CoapplicantIncome 	Additional applicant's monthly salary/income 	1508; 2358; ...
- LoanAmount 	Loan amount 	128; 66; ...
- Loan_Amount_Term 	The loan's repayment period (in days) 	360; 120; ...
- Credit_History 	Records of previous credit history
- (0: bad credit history, 1: good credit history) 	0; 1
- Property_Area 	The location of property
- (Rural/Semiurban/Urban) 	Rural; Semiurban; Urban
- Loan_Status 	Status of loan
- (Y: accepted, N: not accepted) 	Y; N 


## Environment Configuration
- Installing virtual Env
    - pip install pipenv 

- Installing Packages
    - pipenv install jupyter notebook pandas pyarrow numpy matplotlib seaborn scikit-learn

- Starting Virtual Env
    - pipenv shell 

- Starting Notebook
    - jupyter-notebook 

- Stoping Notebook 
    - Ctrl+c

- Deactiving Virtual Env
    - exit