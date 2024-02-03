# Real Estate Price Prediction Project
## Introduction
Creating a Machine Learning model to predict the home prices in Lahore, Pakistan. We are going to use the dataset from Kaggle.com. We are also going to create a simple user interface which will provide access to our model for predictions.

### Data science concepts used in this project

- Data loading and cleaning
- Outlier detection and removal
- Feature engineering
- Dimensionality reduction
- K fold cross validation

### Technology and tools used in this project

- Python
- Numpy and Pandas for data cleaning
- Matplotlib for data visualization
- Sklearn for model building
- Google Colaboratory Notebook

## About Dataset
Our data set consists of 9 features and 13320 entries. Out of 9 features; 3 have integer values, 1 has float values and 6 have categorical values. Thus, the output for shape of our dataset is 
```bash
(13320,9)
```
Now we will find unique values & count of required features before moving to data preprocessing.


## Data Preprocessing:
Following Preprocessing steps were performed on our dataset:

- Dropping irrelevant columns from our dataset reducing features to 5
- Dropping Null and missing values
- Handling or Dropping outliers using Feature engineering and other various methods
- Adding a new feature for calculating price per sqft
- Performing Dimensionality Reduction for reducing dimensions
- Using one-hot encoding to handle categorical features.

## Model Training:
Training on dataset was performed as we implemented Linear Regression model after splitting dataset into training and testing:

## Model Evaluation:
Using K Fold cross validation to measure accuracy of our Linear Regression model 

## Testing

Testing our model by  giving random inputs to calculate predicted house prices

## User interface Widget

Creating a user interface widget to select required values using Dropdowns and Sliders and then predict required house price according to selected data




