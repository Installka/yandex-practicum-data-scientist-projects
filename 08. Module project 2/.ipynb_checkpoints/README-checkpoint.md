# Module project 2

__Gold ore recovery rate prediction__

__Client__ - [Zyfra](https://www.zyfra.com).

__Input data__ - data with parameters of mining and purification of gold ore.

__Target__ - prediction of the recovery rate of gold from gold ore.

__What's done__:
- EDA:
    - parameters description;
    - correctness of the enrichment efficiency calculation check;
    - analysis of features not available in the test sample;
    - distributions check.
- data preprocessing - errors correction, outliers removal, NaN removal, etc.
- data analysis:
    - changes in the concentration of metals at various stages of purification;
    - comparison of the size distribution of raw material granules on the training and test samples;
    - study of the total concentration of all substances at different stages of processing.
- 3 machine learning models fitted and compared on flotation stage data and on final stage data (with conctant model check, custom sMAPE scorer, sklearn Pipline usage and 5-fold GridSearchCV usage):
    - logistic regression;
    - decision tree;
    - random forest.
- best model tested on test sample;
- sMAPE:
    - for result of flotation recovery efficiency - 6.14%;
    - for the final recovery efficiency - 8.95%.
    - final value (both stages) on the training set - 8.25%.
    - final value (both stages) on the test sample - 7.28%.

__Tools used__ - pandas, NumPy, Matplotlib, SciPy, scikit-learn.

__Models used__ - Linear Regression, Decision Tree Regressor, Random Forest Regressor.