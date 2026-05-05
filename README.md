# Heart Disease Prediction Final Project

## Project Description
This project uses a heart disease dataset to predict whether a patient has heart disease based on medical features such as age, cholesterol, blood pressure, chest pain type, maximum heart rate, and other health indicators.

## Dataset
The dataset used is `heart.csv`. It contains 302 patient records and 14 columns. The target variable is `target`, where:
- `0` = no heart disease
- `1` = heart disease

## Methods
The project includes:
- Data cleaning and wrangling
- Exploratory data analysis (EDA)
- Visualizations
- Baseline model
- Logistic Regression model
- Model evaluation using accuracy, precision, recall, F1-score, confusion matrix, and classification report

## Model Results
The Logistic Regression model achieved:
- Accuracy: 77%
- Precision: 70%
- Recall: 90%
- F1 Score: 79%

## Key Findings
The model had a high recall score, meaning it was good at identifying patients with heart disease. This is important because missing a possible heart disease case could be more serious than a false alarm.

## Files
- `final project.ipynb` — Jupyter notebook with full analysis
- `heart.csv` — dataset used for the project
- `README.md` — project explanation
