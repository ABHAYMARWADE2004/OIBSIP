# Iris Flower Classification

## Objective

The objective of this project is to build a machine learning classification model that can identify iris flower species based on their physical measurements.

The model classifies flowers into three species:
- Setosa
- Versicolor
- Virginica


## Dataset

The Iris dataset is a built-in dataset available in Scikit-learn.

It contains:
- 150 flower samples
- 4 input features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

Target classes:
- Setosa
- Versicolor
- Virginica


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


## Machine Learning Models Used

Two classification algorithms were implemented:

1. Logistic Regression
2. Random Forest Classifier


## Project Workflow

1. Loaded the Iris dataset using Scikit-learn.
2. Performed Exploratory Data Analysis (EDA).
3. Checked dataset shape, data types, null values, and descriptive statistics.
4. Created visualizations using Seaborn and Matplotlib.
5. Analyzed feature importance and discriminative features.
6. Split the dataset into training and testing sets.
7. Trained Logistic Regression and Random Forest models.
8. Evaluated the models using accuracy, confusion matrix, precision, recall, and F1-score.
9. Compared model performance and selected the best-performing model.


## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-score


## Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 93.33% |
| Random Forest Classifier | 90.00% |


## Best Performing Model

Based on The Test Accuracy, Logistic Regression was selected as the best-performing model With an Accuracy of 93.33%.




## Conclusion

The Iris Flower Classification Project Successfully demonstrates how machine Learning Classification algorithms can be used to predict flower species based on physical measurements.

Exploratory Data Analysis showed that petal length and petal width are highly useful features for distinguishing between different iris species.



----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

---

# Data Science Task 2 — Unemployment Analysis With Python

## Conclusion

The Analysis of Unemployment Data in India Provides Insights Into Regional Differences, Monthly Trends, And the Impact Of The COVID-19 Pandemic On The Labour Market.

## Dataset

The Project Uses the "Unemployment in India" Dataset Containing Information About Unemployment Rate, Estimated Employment, Labour Participation Rate, Region, And Date.

## Key Analysis

- Correlation Analysis Between Unemployment Rate, Estimated Employment, and Labour Participation Rate.
- COVID-19 Impact Analysis using Pre-COVID and Post-COVID Periods.
- Month-wise Average Unemployment Rate Analysis.
- Region-wise Average Unemployment rate Analysis.
- Time-series analysis of Maharashtra, Uttar Pradesh, and West Bengal.
- Top 10 Regions with the Highest Average Unemployment Rate.

## Key Findings

- COVID-19 Had a Noticeable Impact on Unemployment and Employment Conditions in India.
- Different Regions Showed Different Unemployment Patterns.
- The Unemployment Rate Varied Considerably Across The Available Months.
- The Correlation between Unemployment Rate, Employment, And Labour participation Rate Was Weak.
- The top 10 regions showed Comparatively higher Average Unemployment rates.
- Maharashtra, Uttar Pradesh, and West Bengal Showed Different Unemployment Trends Over Time.

## Objective

The Objective of This Project is To Perform Exploratory Data Analysis (EDA) on Unemployment Data in India to identify Regional And Temporal Trends And Understand The Impact Of The COVID-19 Pandemic on Unemployment Rates.

## Project Structure

```text
DataScience-Task2-UnemploymentAnalysis/
│
├── screenshots/
│   ├── Correlation_Heatmap.png
│   ├── Covid_Comparison.png
│   ├── Monthly_Trend.png
│   ├── Region_Average.png
│   ├── Time_Series.png
│   └── Top_10_Regions.png
│
├── TASK_2_Unemployment_Analysis.ipynb
└── unemployment.csv

## Screenshots

### Correlation Heatmap

![Correlation Heatmap](DataScience-Task2-UnemploymentAnalysis/screenshots/Correlation_Heatmap.png)

### Covid Comparison

![Covid Comparison](DataScience-Task2-UnemploymentAnalysis/screenshots/Covid_Comparison.png)

### Monthly Trend

![Monthly Trend](DataScience-Task2-UnemploymentAnalysis/screenshots/Monthly_Trend.png)

### Region Average

![Region Average](DataScience-Task2-UnemploymentAnalysis/screenshots/Region_Average.png)

### Time Series

![Time Series](DataScience-Task2-UnemploymentAnalysis/screenshots/Time_Series.png)

### Top 10 Regions

![Top 10 Regions](DataScience-Task2-UnemploymentAnalysis/screenshots/Top_10_Regions.png)

## Technologies Used

- Jupyter Notebook
- Matplotlib
- Pandas
- Python
- Seaborn

## Conclusion

Overall, the Project Demonstrates How Python-Based Exploratory Data Analysis Can Be Used to Identify Unemployment Patterns, Regional Differences, Temporal Trends, And The Impact of COVID-19 on India's Labour Market.
