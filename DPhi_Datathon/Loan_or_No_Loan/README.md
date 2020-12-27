# [Loan Approve or No Loan?](https://dphi.tech/practice/challenge/54#problem)

Predict if the applicant should be granted a loan or not.

### **Content**

A loan application is used by borrowers to apply for a loan. Through the loan application, borrowers reveal key details about their finances to the lender. The loan application is crucial to determining whether the lender will grant the request for funds or credit.

![img](https://github.com/AnilKumarTeegala/My-Learnings/blob/master/DPhi_Datathon/img/loan.png)

------

### **Problem Statement**

The director of SZE bank identified that going through the loan applications to filter the people who can be granted loans or need to be rejected is a tedious and time-consuming process. He wants to automate it and increase his bank’s efficiency. After talking around a bit, your name pops up as one of the few data scientists who can make this possible within a limited time. Will you help the director out? 

------

### **Objective**

The idea behind this ML project is to build an ML model and web application that the bank can use to classify if a user can be granted a loan or not.

------

### **Evaluation Criteria**

Submissions are evaluated using F1 Score.

How do we do it? 

Once we release the data, anyone can download it, build a model, and make a submission. We give competitors a set of data (training data) with both the independent and dependent variables. 

We also release another set of data (test dataset) with just the independent variables, and we hide the dependent variable that corresponds with this set. You submit the predicted values of the dependent variable for this set and we compare it against the actual values. 

The predictions are evaluated based on the evaluation metric defined in the datathon.

### **About the Data**

The dataset contains information about Loan Applicants. There are 12 independent columns and 1 dependent column. This dataset includes attributes like Loan ID, gender, if the loan applicant is married or not, the level of education, applicant’s income etc.

#### **Data Description**

- **Loan_ID**: A unique ID assigned to every loan applicant
- **Gender**: Gender of the applicant (Male, Female)
- **Married**: The marital status of the applicant (Yes, No)
- **Dependents**: No. of people dependent on the applicant (0,1,2,3+)
- **Education**: Education level of the applicant (Graduated, Not Graduated)
- **Self_Employed**: If the applicant is self-employed or not (Yes, No)
- **ApplicantIncome**: The amount of income the applicant earns
- **CoapplicantIncome**: The amount of income the co-applicant earns
- **LoanAmount**: The amount of loan the applicant has requested for
- **Loan_Amount_Term**: The no. of days over which the loan will be paid
- **Credit_History**: A record of a borrower's responsible repayment of debts (1- has all debts paid, 0- not paid)
- **Property_Area** : The type of location where the applicant’s property lies (Rural, Semiurban, Urban)
- **Loan_Status**: Loan granted or not (Y, N)
