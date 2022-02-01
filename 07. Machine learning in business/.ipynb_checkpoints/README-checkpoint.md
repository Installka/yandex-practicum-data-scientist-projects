# Machine learning in business

__Determining the place for a new oil well__

__Client__ - oil company.

__Input data__ - oil samples in 3 regions.

__Target__ - build a ML model to help determine the region where mining will generate the most profit. Analyze the potential rewards and risks with the Bootstrap technique.

__What's done__:
- data exploring (distributions check, duplicates check, etc.);
- data splitting to independent and target features and to training, validation and test samples;
- data scaling;
- linear regression fitted on data from 3 regions. Results compared:
- volume of raw materials for break-even development of a new well calculated;
- profits and risks calculated with Bootstrap technique.
- best region have been chosen.

__Tools used__ - pandas, NumPy, Matplotlib, scikit-learn.

__Models used__ - Linear Regression.