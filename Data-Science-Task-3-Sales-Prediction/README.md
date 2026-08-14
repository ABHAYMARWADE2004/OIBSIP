# Sales Prediction Using Python

## Objective

Build a Regression Model To Predict Product Sales Based On Advertising Expenditure Across Different Media Channels: TV, Radio, And Newspaper.

## Dataset

The Project Uses The Classic `Advertising.csv` Dataset Containing Advertising Expenditure And Sales Data.

### Features

* TV — TV Advertising Spend
* Radio — Radio Advertising Spend
* Newspaper — Newspaper Advertising Spend
* Sales — Product Sales (Target Variable)

## Tools And Technologies

* Jupyter Notebook
* Matplotlib
* Pandas
* Python
* Scikit-learn
* Seaborn

## Project Workflow

1. Data Loading And Exploration
2. Data Cleaning
3. Descriptive Statistics
4. Exploratory Data Analysis
5. Correlation Analysis
6. Train-Test Split
7. Linear Regression
8. Random Forest Regression
9. Model Evaluation
10. Residual Analysis
11. Feature Importance
12. Interpretation And Conclusion

## Models Used

### Linear Regression

Linear Regression Was Trained As the Baseline Regression Model.

### Random Forest Regressor

Random Forest Regressor Was trained As An Additional Regression Model And Achieved Better Performance Than The Linear Regression Model.

## Model Evaluation

### Linear Regression

* MAE: 1.46
* RMSE: 1.78
* R² Score: 0.8994

### Random Forest Regressor

* MAE: 0.62
* RMSE: 0.77
* R² Score: 0.9813

The Random Forest Regressor performed better Than The Linear Regression Baseline Based On The Evaluation Metrics.

## Feature Importance

The Random Forest feature importance analysis showed:

| Feature   | Importance |
| --------- | ---------: |
| TV        |   0.624810 |
| Radio     |   0.362201 |
| Newspaper |   0.012989 |

TV Advertising Had The Highest Importance, Followed By Radio. Newspaper Had the Lowest Importance In The Model.

## Conclusion

The Sales Prediction Project Demonstrates How Machine Learning Can Be Used To Predict Product Sales Based On Advertising Expenditure. Two Regression Models Were Evaluated, and the Random Forest Regressor Achieved Better Predictive Performance Than the Linear Regression Baseline.

The Feature Importance Analysis Showed That TV advertising was the Most Influential Advertising Channel For Predicting Sales In this Dataset.

## Project Structure

```text
Data-Science-Task-3-Sales-Prediction/
│
├── Advertising.csv
├── Sales_Prediction_Using_Python.ipynb
└── README.md
```


## Files

* `Advertising.csv` — Dataset Used For The Project
* `Sales_Prediction_Using_Python.ipynb` — Complete Jupyter Notebook containing Data Analysis, Model Training, Evaluation, Visualizations And Conclusions

