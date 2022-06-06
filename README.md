# Employee-Attrition-Predictor
The entire dataset has broken down into 2 sub-datasets: One containing the numerical features and the other one containing the categorical features

Proper data visualization has been performed for the numerical data to observe correlations between the features and the label and between each individual feature and the others.

To handle with categorical data, appropriate encoding techniques have been incorporated. These include:
1. OneHotEncoding - for nominal data
2. Label Encoding - for ordinal data

The 2 dataframes are then merged into one master dataframe and unnecessary columns are dropped. Then we'll apply train_test_split of this master dataframe.

The following binary classification machine learning algorithms have been used:
1. Logistic Regression
2. Decision Trees
3. Random Forest
4. Gradient Boosting
5. XGBoost
6. KNN

For each model appropriate hyperparameter tuning has been performed with GridSearchCV and 5 fold cross-validation.

Since this is an imbalanced dataset, appropriate sampling techniques have been incorporated to select the optimal model.
