# boston_housing
### Udacity Machine Learning Engineer Nanodegree
#### Unit 1: Model evaluation and validation


### Project: Predicting Boston Housing Prices


This project requires Python, the Python file ‘visuals.py’ provided by Udacity and the following libraries:
-	NumPy
-	Pandas
-	Matplotlib
-	Scikit-learn

### Data
Data are provided by Udacity, as a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).
There are 489 samples and three features:
1.	RM: Average number of rooms per dwelling
2.	LSTAT: Percentage of population considered lower status
3.	PTRATIO: Pupil-teacher ratio by town

The target variable is:

4.	MEDV: Median value of owner-occupied homes

## Project Overview
The aim of this project is to evaluate the performance and predictive power of a decision tree regressor model trained and tested on the provided Boston Housing dataset.

Within the project:
-	The coefficient of determination (r2_score) is used as performance metric.
-	Learning curves for a decision tree model with different ‘max_depth’ values and training set sizes are analysed for variance and bias.
-	Complexity curves for a decision tree that has been trained and validated on the training data using different maximum depths are evaluated to select ‘max_depth’ optimal value.
-	Grid Search technique is discussed and then used to optimise the ‘max_depth’ parameter for the decision tree model. 

This first Udacity project of the Machine Learning Engineer Nanodegree was designed for students to start working with datasets in Python and start applying basic machine learning techniques, using NumPy and Scikit-Learn libraries. The focus was to first practice analysing and interpreting model performance.
