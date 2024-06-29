# Diabetes-Prediction-Model-using-Logistic-Regression
This project leverages the Pima Indian Diabetes dataset and logistic regression Algorithm to provide accurate predictions and valuable insights. 

## Dataset Description

The dataset includes the following features:
- **Pregnancies**: Number of times the patient has been pregnant.
- **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skinfold thickness (mm).
- **Insulin**: 2-Hour serum insulin (mu U/ml).
- **BMI**: Body Mass Index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: Diabetes pedigree function (a function which scores likelihood of diabetes based on family history).
- **Age**: Age (years).
- **Outcome**: Class variable (0 if non-diabetic, 1 if diabetic).

## Project Overview

This project follows these main steps:
1. **Data Splitting**: Splitting the dataset into training and testing sets.
2. **Model Training**: Training a logistic regression model on the processed data.
3. **Model Evaluation**: Evaluating the model's performance using metrics like accuracy, precision, recall, and F1-score.
4. **Results**: Analyzing the results and making predictions.

```
# import the class
from sklearn.linear_model import LogisticRegression

# instantiate the model, increasing max_iter
logreg = LogisticRegression(random_state=16, max_iter=1000) # Increased max_iter

# fit the model with data
logreg.fit(X_train, y_train)

y_pred = logreg.predict(X_test)
```

## Acknowledgements

This project is based on the Pima Indian Diabetes dataset available on [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database). Also special thanks to datacamp for their insightful learning materials. See the attached file for details.


