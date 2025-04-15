# Loan-Tap-Logisitic-Regression

● LoanTap is at the forefront of offering tailored financial solutions to millennials.
● Their innovative approach seeks to harness data science for refining their credit
underwriting process.
● The focus here is the Personal Loan segment. A deep dive into the dataset can
reveal patterns in borrower behavior and creditworthiness.
● Analyzing this dataset can provide crucial insights into the financial behaviors,
spending habits, and potential risk associated with each borrower.
● The insights gained can optimize loan disbursal, balancing customer outreach
with risk management.

Dataset Explanation: LoanTapData.csv
1. loan_amnt: Amount borrower applied for.
2. term: Loan duration (36 or 60 months).
3. int_rate: Interest rate on loan.
4. installment: Monthly repayment amount.
5. grade: LoanTap assigned loan grade (Risk ratings by LoanTap.)
6. sub_grade: LoanTap assigned loan grade (Risk ratings by LoanTap.)
7. emp_title: Borrower's job title.
8. emp_length: Duration of borrower's employment (0-10 years).
9. home_ownership: Borrower's housing situation (own, rent, etc.).
10. annual_inc: Borrower's yearly income.
11. verification_status: Whether borrower's income was verified.
12. issue_d: Loan issuance month.
13. loan_status: Current status of the loan.
14. purpose: Borrower's reason for the loan.
15. title: The loan's title provided by the borrower.
16. dti (Debt-to-Income ratio): Monthly debt vs. monthly income ratio.
17. earliest_cr_line: Date of borrower's oldest credit account.
18. open_acc: Number of borrower's active credit lines.
19. pub_rec: Negative records on borrower's public credit profile.
20. revol_bal: Total credit balance.
21. revol_util: Usage percentage of 'revolving' accounts like credit cards.
22. total_acc: Total number of borrower's credit lines.
23. initial_list_status: Loan's first category ('W' or 'F').
24. application_type: Individual or joint application.
25. mort_acc: Number of borrower's mortgages.
26. pub_rec_bankruptcies: Bankruptcy records for borrower.
27. Address: Borrower's location.

What is Expected?

Assuming you are a data scientist at LoanTap, you are tasked with analyzing the
dataset to determine the creditworthiness of potential borrowers. Your ultimate objective
is to build a logistic regression model, evaluate its performance, and provide actionable
insights for the underwriting process.

Questionnaire

1. What percentage of customers have fully paid their Loan Amount?
2. Comment about the correlation between Loan Amount and Installment features.
3. The majority of people have home ownership as _______.
4. People with grades ‘A’ are more likely to fully pay their loan. (T/F)
5. Name the top 2 afforded job titles.
6. Thinking from a bank's perspective, which metric should our primary focus be
on..
c. Visual
Representations

Visuals can often convey
information more effectively
than numbers alone.

Utilize well-labeled charts,
plots, and graphs (like ROC
AUC curve and Precision
recall curve) to visualize and
emphasize key insights

d. Trade-off Analysis Business decisions often
involve trade-offs. It's crucial
to understand the balance
between risk (false positives)
and opportunity (financing
more individuals).

Highlight the implications of
false positives and false
negatives. Discuss strategies
to strike a balance, such as
adjusting the classification
threshold.

e. Recommendations End with actionable
recommendations derived
from your analysis

Recommend strategies to
improve loan approval
processes, mitigate risks, or
capitalize on opportunities.
Support these
recommendations with
evidence from your analysis.

f. Feedback Loop Continuous improvement is

key in analytics.

Propose methods for
continuously monitoring the
model's performance over
time and iterating based on
new data or changing
business needs.

1. ROC AUC
2. Precision
3. Recall
4. F1 Score

7. How does the gap in precision and recall affect the bank?
8. Which were the features that heavily affected the outcome?
9. Will the results be affected by geographical location? (Yes/No)
