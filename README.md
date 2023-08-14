# Loan Risk Detector Analysis

**Problem Statement:**

Our work proposes a Machine Learning model that predicts defaulters which would aid the financial industry to prevent financial loss.

**Data Description:**

- id : To uniquely identify every loan in the dataset.
- member_id : To identify the borrower to who has applied for the loan.
- loan_amnt : The listed amount of the loan applied for by the borrower.
- funded_amnt : The amount that was sanctioned by the LC.
- term : The number of payments on the loan. Values are in months and can be either 36 or 60.
- int_rate : Interest Rate on the loan
- installment : The monthly payment owed by the borrower if the loan originates.
- grade : LC assigned loan grade which depends on the borrower’s credit score.
- sub_grade : LC assigned loan subgrade
- emp_title : The job title supplied by the Borrower when applying for the loan.*
- emp_length : Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.
- home_ownership : The home ownership status provided by the borrower during registration or obtained from the credit report. Our values are: RENT, OWN, MORTGAGE, OTHER
- annual_inc : The self-reported annual income provided by the borrower during registration.
- verification_status : Indicates if income was verified by LC, not verified, or if the income source was verified
- issue_d : The month which the loan was funded
- loan_status : Current status of the loan
- purpose : A category provided in the form of a code to indicate the purpose for the loan.
- title : Explaining the ‘purpose’ of the loan.
- dti : The debt to income ratio is the ratio of how much the borrower owes every month to the borrower’s income every month.
- delinq_2yrs : The number of delinquencies(late installment payment) by the borrower in the past 2 years.
- earliest_cr_line : The month-year the borrower's earliest reported credit line was opened
- inq_last_6mths : Inquiries for loans made by the borrower over the past 6 months.
- mths_since_last_delinq : Months that have passed since the borrower last missed the timely payment of installment.
- open_acc : The number of open credit lines in the borrower’s credit file.
- pub_rec Number of derogatory public records
- revol_bal : Total credit revolving balance
- revol_util : Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.
- total_acc : The total number of credit lines currently in the borrower's credit file
- initial_list_status : The initial listing status of the loan. Possible values are – W(whole), F(fractional)
- out_prncp : Remaining outstanding principal for total amount funded
- total_pymnt : Payments received to date for the total amount funded.
- total_rec_prncp : Principal received till date.
- total_rec_int Interest received till date.
- total_rec_late_fee : Late fees received to date.
- recoveries : Total recovery procedures initiated against the borrower.
- collection_recovery_fee : The fees collected during the recovery procedures.
- last_pymnt_d The last month when payment was received.
- last_pymnt_amnt : The last payment amount received.
- next_pymnt_d : Next scheduled payment date.
- last_credit_pull_d : The most recent month LC pulled credit for this loan
- collections_12_mths_ex_med : Number of collections in 12 months excluding medical collections
- mths_since_last_major_derog : Months since most recent 90-day delinquency or worse rating
- application_type Indicates whether the loan is an individual application or a joint application with two co-borrowers
- annual_inc_joint : The combined self-reported annual income provided by the co-borrowers during registration
- dti_joint : A ratio calculated using the co-borrowers' total monthly payments on the total debt obligations, excluding mortgages and the requested LC loan, divided by the co-borrowers' combined self-reported monthly income
- acc_now_delinq : The number of accounts on which the borrower is now delinquent
- tot_coll_amt : Total collection amounts ever owed by the borrower
- tot_cur_bal : Total current balance of all accounts owned by the borrower
- total_rev_hi_lim : Total high credit/credit limit

**Dataset Link:** https://www.kaggle.com/datasets/hetvigandhi03/loan-risk-analysis-dataset-real-world-data
