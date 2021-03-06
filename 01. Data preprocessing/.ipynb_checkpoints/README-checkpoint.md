# Data preprocessing

__Borrowers reliability research__

__Client__ - bank credit department.

__Input data__ - customers solvency statistics.

__Target__ - determine whether the marital status and number of children of the customer affects the fact of repayment of the loan on time.

__What's done__:
- data preprocessing:
    - detection, correction and removal of missing values;
    - data types correction;
    - duplicates detection and removal;
    - strings features lemmatization;
    - category features obtention from other features.
- 4 hypotheses were tested and rejected:
    - about the relationship between the presence of children and loan repayment on time;
    - about the relationship between marital status and loan repayment on time;
    - about the relationship between income level and loan repayment on time;
    - about the relationship between the purpose of obtaining a loan and its repayment on time.

__Tools used__ - pandas, pymystem3.