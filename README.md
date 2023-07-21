# Predicting-Credit-Card-Approvals


This notebook builds a machine learning model to predict if a credit card application will get approved or not based on customer attributes.

## Data

The credit card approval dataset is obtained from the UCI Machine Learning Repository. It contains information on 690 applicants including demographic features like Gender, Age, Debt, Income and attributes like Credit Score. 

## Methods

The main steps involved in building the prediction model are:

- Data inspection: Checking for missing values, data types and statistical properties. Missing values are imputed accordingly.

- Preprocessing: Converting categorical features to dummy variables, splitting into train and test sets, feature scaling using MinMaxScaler.

- Model Building: Fitting a Logistic Regression model on the training data.

- Evaluation: Evaluating classifier performance using accuracy score and confusion matrix. 

- Tuning: Gridsearching over Logistic Regression hyperparameters like tol and max_iter to find best model.

## Results

The final Logistic Regression model achieves 100% accuracy in predicting credit card approvals on the test set. The confusion matrix shows perfect classification for both approved and denied status.

## Conclusion

The notebook provides a simple machine learning workflow for a classification problem. The final model demonstrates excellent predictive power. Further improvements can focus on trying different algorithms like Random Forest, obtaining more data, and adding additional predictive features.

