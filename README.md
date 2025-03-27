# LoanTap - Logistic Regression

### Introduction:

Loantap is a leading financial technology company based in India, specializing in providing flexible and innovative loan products to individuals and businesses. With a focus on customer-centric solutions, Loantap leverages technology to offer hassle-free borrowing experiences, including personal loans, salary advances, and flexible EMI options. Their commitment to transparency, speed, and convenience has established them as a trusted partner for borrowers seeking efficient financial solutions.

- LoanTap is at the forefront of offering tailored financial solutions to millennials.

- Their innovative approach seeks to harness data science for refining their credit underwriting process.

- The focus here is the Personal Loan segment. A deep dive into the dataset can reveal patterns in borrower behavior and creditworthiness.

- Analyzing this dataset can provide crucial insights into the financial behaviors, spending habits, and potential risk associated with each borrower.

- The insights gained can optimize loan disbursal, balancing customer outreach with risk management.



### Our Task:

As a data scientist at LoanTap,  you are tasked with analyzing the dataset to determine the creditworthiness of potential borrowers. Your ultimate objective is to build a logistic regression model, evaluate its performance, and provide actionable insights for the underwriting process.

        
### Features of the dataset:

- Column Profiling:

| Feature | Description |
|:--------|:------------|
| loan_amnt | The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value|
| term | The number of payments on the loan. Values are in months and can be either 36 or 60|
| int_rate | Interest Rate on the loan|
| installment | The monthly payment owed by the borrower if the loan originates|
| grade | LoanTap assigned loan grade|
| sub_grade | LoanTap assigned loan subgrade|
| emp_title |The job title supplied by the Borrower when applying for the loan|
| emp_length | Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years|
| home_ownership | The home ownership status provided by the borrower during registration or obtained from the credit report|
| annual_inc | The self-reported annual income provided by the borrower during registration|
| verification_status | Indicates if income was verified by LoanTap, not verified, or if the income source was verified|
| issue_d | The month which the loan was funded|
| loan_status | Current status of the loan - Target Variable|
| purpose | A category provided by the borrower for the loan request|
| title | The loan title provided by the borrower|
| dti | A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LoanTap loan, divided by the borrower’s self-reported monthly income|
| earliest_cr_line |The month the borrower's earliest reported credit line was opened|
| open_acc | The number of open credit lines in the borrower's credit file|
| pub_rec | Number of derogatory public records|
| revol_bal | Total credit revolving balance|
| revol_util | Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit|
| total_acc | The total number of credit lines currently in the borrower's credit file|
| initial_list_status | The initial listing status of the loan| Possible values are – W, F|
| application_type | Indicates whether the loan is an individual application or a joint application with two co-borrowers|
| mort_acc | Number of mortgage accounts|
| pub_rec_bankruptcies | Number of public record bankruptcies|
| Address| Address of the individual|
