Loan Prediction Model


"You really impressed the management of European Bank with the last deliverable, and they have now requested you to assist further with analyzing their loans data. We have dealt with European Bank before, but as a recap, they connects people who need money (borrowers) with people who have money (investors). Now bank would want to invest in people who showed a profile of having a high probability of paying back."
For this project we will be using publicly available data from LendingClub(2007-2010) and predict whether or not the borrower paid back their loan in full. Bank is looking for a model that will help to predict this

Dataset Description:
credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
installment: The monthly installments owed by the borrower if the loan is funded.
log.annual.inc: The natural log of the self-reported annual income of the borrower.
dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
fico: The FICO credit score of the borrower.
days.with.cr.line: The number of days the borrower has had a credit line.
revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).



The goal is to use these features to predict whether an applicant will default on their loan.

Project Structure
```
Loan-Prediction-Model/
│
├── data/
│   ├── train.csv                # Training dataset
│   └── test.csv                 # Testing dataset
│
├── notebooks/
│   ├── EDA.ipynb                # Exploratory Data Analysis
│   ├── Model_Building.ipynb      # Model development and training
│
├── src/
│   ├── data_preprocessing.py     # Data cleaning and preprocessing
│   ├── model.py                  # Machine learning model code
│   └── evaluation.py             # Model evaluation metrics
│
├── README.md                     # Project README file
├── requirements.txt              # Required libraries and dependencies
└── model.pkl                     # Saved machine learning model
```



Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebooks




