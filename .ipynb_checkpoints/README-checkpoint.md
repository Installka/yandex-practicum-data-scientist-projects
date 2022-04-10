# yandex-practicum-data-scientist-projects
Projects from [Yandex.Practicum Data Scientist course](https://practicum.yandex.ru/data-scientist/). 
 
Unfortunately, I can’t post datasets from most of the projects here because of limitations in the [Yandex.Practicum terms of use](https://yandex.ru/legal/praktikum_termsofuse/) (clause 4.1). But in some cases datasets were pulled from open sources (project 6), so you can download data and notebook and fully run it.
 
## Description of projects
### [Project 0. Fundamentals of Python and data analysis](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/00.%20Fundamentals%20of%20Python%20and%20data%20analysis)
__Music of big cities__
- Client - [Yandex.Music](https://music.yandex.ru/);
- Input data - music listening data for Moscow and St. Petersburg;
- Target - researching user preferences.

Tools used - pandas.

### [Project 1. Data preprocessing](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/01.%20Data%20preprocessing)
__Borrowers reliability research__

- Client - bank credit department;
- Input data - customers solvency statistics;
- Target - determine whether the marital status and number of children of the customer affects the fact of repayment of the loan on time.

Tools used - pandas, pymystem3.

### [Project 2. Exploratory data analysis](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/02.%20Exploratory%20data%20analysis)
__Analysis of apartment advertisements__

- Input data - [Yandex.Nedvizhimost](https://realty.yandex.ru/) service data: archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years;
- Target - determine the parameters for determining the market value of real estate.

Tools used - pandas, pymystem3.

### [Project 3. Statistical data analysis](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/03.%20Statistical%20data%20analysis)
__Definition of a prospective tariff for a telecom company__ 

- Client - federal mobile operator;
- Input data - data from 500 users: who they are, where they come from, what tariff they use, how many calls and messages each one sent in 2018;
- Target - analyze customer behavior and conclude - which tariff is better.

Tools used - pandas, NumPy, Matplotlib, SciPy.

### [Project 4. Module project 1](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/04.%20Module%20project%201)
__Computer games market research__

- Client - computer games online store;
- Input data - historical game sales data, user and expert ratings, genres and platforms (e.g. Xbox or PlayStation);
- Target - identify patterns governing the success of the game.

Tools used - pandas, NumPy, Matplotlib, seaborn, SciPy.

### [Project 5. Introduction to machine learning](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/05.%20Introduction%20to%20machine%20learning)
__Tariff recommendation__

- Client - federal mobile operator.
- Input data - data on the behavior of customers who have already switched to these tariffs (from the project 3).
- Target - build a model for the classification problem, which will choose the appropriate tariff.

Tools used - pandas, scikit-learn.

Models used - Logistic Regression, Decision Tree Classifier, Random Forest Classifier.

### [Project 6. Supervised learning](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/06.%20Supervised%20learning)
__Customer churn__

- Client - bank;
- Input data - historical data on customer behavior and termination of contracts with the bank (this data pulled from [Kaggle](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling), so you can download it from Kaggle or from [repository](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/06.%20Supervised%20learning/Churn_Modelling.csv) and fully run this project's notebook);
- Target - predict whether the client will leave the bank in the near future or not.

Tools used - pandas, NumPy, Matplotlib, scikit-learn, plotly, seaborn.

Models used - Logistic Regression, Decision Tree Classifier, Random Forest Classifier.

### [Project 7. Machine learning in business](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/07.%20Machine%20learning%20in%20business)
__Determining the place for a new oil well__
- Client - oil company;
- Input data - oil samples in 3 regions;
- Target - build a ML model to help determine the region where mining will generate the most profit. Analyze the potential rewards and risks with the Bootstrap technique.

Tools used - pandas, NumPy, Matplotlib, scikit-learn.

Models used - Linear Regression.

### [Project 8. Module project 2](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/08.%20Module%20project%202)
__Gold ore recovery rate prediction__
- Client - [Zyfra](https://www.zyfra.com);
- Input data - data with parameters of mining and purification of gold ore;
- Target - prediction of the recovery rate of gold from gold ore.

Tools used - pandas, NumPy, Matplotlib, SciPy, scikit-learn.

Models used - Linear Regression, Decision Tree Regressor, Random Forest Regressor.

### [Project 9. Linear algebra](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/09.%20Linear%20algebra)
__Customer data protection__
- Client - insurance company;
- Input data - data with info about customer;
- Target - develop a method for transforming data so that it is difficult to recover personal information from them and the quality of machine learning models does not deteriorate.

Tools used - pandas, NumPy, scikit-learn.

Models used - Linear Regression.

### [Project 12. Machine learning for texts](https://github.com/Installka/yandex-praktikum-data-scientist-projects/tree/main/12.%20Machine%20learning%20for%20texts)
__Toxic comments detection__
- Client - online store;
- Input data - cased comments;
- Target - build a model for classifying comments into positive and negative.

Tools used - pandas, NumPy, Matplotlib, re, NLTK, SciPy, PyTorch, transfromers, LightGBM, scikit-learn.

Models used - LightGBM Classifier, BERT, Logistic Regression, Decision Tree Classifier, Random Forest Classifier.

### [Project 15. Final project](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/15.%20Final%20project)
__Telecom operator customer churn prediction__

- Client - telecom operator.
- Input data - personal data of clients, information about their tariffs and contracts.
- Target - learn to predict customer churn.

Tools used - pandas, NumPy, Matplotlib, scikit-learn, CatBoost.

Models used - Logistic Regression, Decision Tree Classifier, Random Forest Classifier, CatBoost Classifier, VotingClassifier.
