# University_Admission_Prediction_ML_Regularization

## Project Overview

The University Admission Prediction project is a Flask-based web application designed to predict the likelihood of admission to graduate programs based on individual student profiles. It employs various regression techniques, including Linear, Ridge, and Lasso regression, to analyze features such as GRE and TOEFL scores, university ratings, SOP and LOR strengths, CGPA, and research experience. This application aims to assist students in understanding their chances of getting into graduate school by leveraging machine learning for educational forecasting.

## Independent Features

1. GRE Score: Test score for graduate school applications.
2. TOEFL Score: English proficiency test score.
3. University Rating: Rating of the university applied to.
4. SOP: Statement of purpose strength.
5. LOR: Strength of letters of recommendation.
6. CGPA: Undergraduate cumulative grade point average.
7. Research: Whether the student has research experience.


## Algorithms Used

1. Linear Regression: Predicts continuous outcomes.
2. Ridge Regression: Reduces the model complexity, handles multicollinearity.
3. Lasso Regression: Performs the variable selection, improves prediction accuracy and in feature selection.


## Steps Involved

1. Data Ingestion: Importing the dataset for analysis.
2. Data Preprocessing: Clean and prepare data.
3. Exploratory Data Analysis: Analyze data to find patterns.
4. Feature Engineering: Modify or create new features.
5. Model Building: Constructing the models to predict outcomes.
6. Model Evaluation: Assessing the model accuracy and performance.
7. Model Deployment: Deploying the model in a web application.

## Commands Used

To install the dependencies

```
pip install -r requirements.txt
```

To run the Flask Web Application

```
python app.py
```

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request.