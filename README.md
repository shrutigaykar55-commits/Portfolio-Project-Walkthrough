# Titanic Survival Prediction using Machine Learning

## Project Overview

This project is based on the famous Titanic dataset from Kaggle. The main aim of the project is to predict whether a passenger survived the Titanic disaster based on different passenger details.

Through this project, I worked on the complete basic machine learning process, starting from data exploration and cleaning to model training and evaluation.

## Dataset

The dataset contains information about Titanic passengers such as:

* Passenger Class
* Gender
* Age
* Number of Siblings/Spouses
* Number of Parents/Children
* Fare
* Port of Embarkation
* Survival Status

The dataset is divided into:

* `train.csv` – Used for training and evaluating the machine learning models
* `test.csv` – Used for making final predictions

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Project Steps

### 1. Data Loading

Loaded the Titanic training and testing datasets using Pandas.

### 2. Data Exploration

Checked the dataset structure, number of rows and columns, statistical information, and missing values.

### 3. Exploratory Data Analysis

Created different visualizations to understand the data, including:

* Survival distribution
* Survival based on gender
* Survival based on passenger class
* Age distribution
* Age and survival relationship
* Fare distribution
* Survival based on embarkation port
* Correlation heatmap

### 4. Data Cleaning

Handled missing values using appropriate imputation techniques.

Categorical data was converted into numerical form so that it could be used by machine learning models.

### 5. Feature Engineering

Created two additional features:

**FamilySize**

`FamilySize = SibSp + Parch + 1`

This represents the total size of the passenger's family on the ship.

**IsAlone**

This feature identifies whether a passenger was travelling alone.

### 6. Machine Learning Models

I trained and compared three classification algorithms:

1. Logistic Regression
2. Decision Tree
3. Random Forest

### 7. Model Evaluation

The models were evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report

The accuracy of each model was compared to identify the best-performing model.

### 8. Final Prediction

The best-performing model was used to predict survival for the passengers in the test dataset.

The final predictions were saved as:

`titanic_submission.csv`

## Project Outcome

This project helped me understand how machine learning can be applied to a real-world classification problem.

I also gained practical experience in:

* Data cleaning
* Exploratory Data Analysis
* Feature engineering
* Handling categorical and numerical data
* Classification algorithms
* Model evaluation
* Making predictions using a trained model

## Conclusion

The Titanic project was a useful introduction to the complete machine learning workflow. It helped me understand how the quality of data and the selection of useful features can affect the performance of a machine learning model.

## Future Improvements

Some possible improvements for this project would be:

* Hyperparameter tuning
* Trying additional machine learning algorithms
* Creating more useful features
* Improving model performance
* Using cross-validation for more reliable evaluation
