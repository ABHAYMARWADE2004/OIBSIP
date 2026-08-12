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


