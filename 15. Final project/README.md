# Final project

__Telecom operator customer churn prediction__

__Client__ - telecom operator.

__Input data__ - personal data of clients, information about their tariffs and contracts.

__Target__ - learn to predict customer churn.

__What's done__:
- EDA performed:
    - analysis of 17 features;
    - types cast;
    - target feature extraction;
    - new features calculation.
- data preprocessing:
    - data merging in one DataFrame with all features;
    - data splitting on independent and target features and on train and test samples;
    - data transformation in pipeline with grid search (OHE and scaling).
- plan for solving the whole task;
- hyperparameters opimization on train sample for 4 models and VotingClassifier for all these models;
- best model choosen from 5 optimized models;
- best model test on test sample with ROC AUC 0.881 and accuracy 0.775;
- report made.

__Tools used__ - pandas, NumPy, matplotlib, scikit-learn, CatBoost.

__Models used__ - Logistic Regression, Decision Tree Classifier, Random Forest Classifier, CatBoost Classifier, VotingClassifier.