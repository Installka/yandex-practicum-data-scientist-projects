# Machine learning for texts

__Toxic comments detection__

__Client__ - online store.

__Input data__ - cased comments.

__Target__ - build a model for classifying comments into positive and negative.

__What's done__:
- EDA and data preprocessing:
    - distributions check;
    - creation of additional features;
    - removal of unnecessary symbols, tokenization and lemmatization;
- 2 transformation methods (TF-IDF and BERT for review) compared on 4 machine learning models (with sklearn Pipline usage, 5-fold GridSearchCV usage and feature importance analysis):
    - logistic regression;
    - decision tree;
    - random forest;
    - LightGBM.
- best F1 with TF-IDF transformation on test sample - 0.765.

__Tools used__ - pandas, NumPy, Matplotlib, re, NLTK, SciPy, PyTorch, transfromers, LightGBM, scikit-learn.

__Models used__ - LightGBM Classifier, BERT, Logistic Regression, Decision Tree Classifier, Random Forest Classifier.