<h3><b>Description</b></h3>

The original dataset contains 1000 entries with 20 categorial/symbolic attributes. In this dataset, each entry represents a person who takes a credit by a bank. Each person is classified as good or bad credit risks according to the set of attributes. Applied the Machine Learning algorithm (LogisticRegression, Decision Tree Classifier, Random Forest Classifier) to predict risk based on the German Credit card users data.

<h3><b> Preprocessing and Training </b></h3>
Reading the German Credit Risk data

Imputing the Null values in the Dataset with Missing.

Studied the relationship between the Dependent and Independent Variable using the Seaborn library.

Change the data type of some of the columns to factor.

Created the dummies for categorical data

Create X (drop wthe target variable) and Y (only target variable).

Splitting the X,y into Train Set and Test Set in 75% and 25% respectively.

Trained the dataset using the LogisticRegression model.

Trained the dataset using Decision Tree Classifier Model.

Predict y using X_test for both the above models. Logistic : accuracy score: 73%, Decision Tree accuracy score: 67%

Build Random Forest Classifier model.

Use GridSearchCV to find the best estimator.

Build the Random Forest Classifier model with best estimator.

Predicting the test using this model. Using the confusion matrix, the accuracy score : 74%

Test data set should be in .csv format


<h3><b>Attachments</b></h3>

1. german_credit_data.csv : Contains the credit card details
2. predicting-credit-risk-model-Python : Python code file
