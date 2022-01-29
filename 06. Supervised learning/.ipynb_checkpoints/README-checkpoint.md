# Supervised learning

__Customer churn__

__Client__ - bank.

__Input data__ - historical data on customer behavior and termination of contracts with the bank (this data pulled from [Kaggle](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling), so you can download it from Kaggle or from [repository](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/06.%20Supervised%20learning/Churn_Modelling.csv) and fully run this project's notebook).

__Target__ - predict whether the client will leave the bank in the near future or not.

__What's done__:
- data preprocessing (cleaning, OHE, scaling, etc.);
- data splitting to independent and target features;
- data splitting to training, validation and test samples;
- 3 machine learning models fitted and compared (with self-made hyperparameters variation, overfitting check and interactive results plotly graph):
    - logistic regression;
    - decision tree;
    - random forest.
- all models were tested with 3 types of balancing methods - class weights, upsampling and downsampling.
- best model tested on test sample and best F1 threshold were found;
- F1 on test sample - 0.6298, AUC-ROC - 0.8663.

__Tools used__ - pandas, NumPy, Matplotlib, scikit-learn, plotly, seaborn.

__Models used__ - Logistic Regression, Decision Tree Classifier, Random Forest Classifier.