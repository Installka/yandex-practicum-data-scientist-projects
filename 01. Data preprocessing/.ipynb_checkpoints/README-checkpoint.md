# Data preprocessing

__Client__ - bank credit department.

__Input data__ - customers solvency statistics.

__What's done__:
- data preprocessing:
    - detection, correction and removal of missing values;
    - data types correction;
    - duplicates detection and removal;
    - strings features lemmatization;
    - category features obtantion from other fatures.
- 4 hypothesis were tested and rejected:
    - about the relationship between the presence of children and loan repayment on time;
    - about the relationship between marital status and loan repayment on time;
    - about the relationship between income level and loan repayment on time;
    - about the relationship between the purpose of obtaining a loan and its repayment on time.

__Tools used__ - pandas, pymystem3.