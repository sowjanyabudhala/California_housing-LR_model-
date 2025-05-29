## 🏡 California Housing Price Prediction using Linear Regression
This project uses the California Housing dataset to predict median house values using Linear Regression. It demonstrates the process of building, evaluating, and interpreting a regression model using fundamental machine learning techniques.

## 📁 Dataset
The dataset is sourced from the California Housing dataset, which contains information collected during the 1990 U.S. Census. Each row represents a block group — the smallest geographical unit used by the US Census Bureau.

## Feature	Description
MedInc	Median income in block group
HouseAge	Median house age in block group
AveRooms	Average number of rooms
AveBedrms	Average number of bedrooms
Population	Population in the block group
AveOccup	Average occupancy (residents per household)
Latitude	Geographical latitude
Longitude	Geographical longitude
MedHouseVal	(Target) Median house value (in $100,000s)

## ✅ Project Workflow
Import Libraries & Load Data
Read the CSV file and inspect for nulls or outliers.

Preprocessing

Features and target (MedHouseVal) separated

Data split into training and test sets

Features scaled using StandardScaler

Model Training

Linear Regression model from sklearn.linear_model

Fit on training data

Model Evaluation
Metrics used:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

Visualization

Scatter plot of predicted vs. actual values

Coefficients printed for interpretation

## 📊 Results
Metric	Value
MAE	~0.52
MSE	~0.51
R²	~0.57

These values may vary slightly based on data splits or preprocessing.

## 📌 How to Run
Clone this repository or download the .ipynb file.

Install the necessary libraries:
pip install pandas scikit-learn matplotlib seaborn

Run the notebook California_housing.ipynb in Jupyter Notebook or any compatible environment.

## 💡 Key Learnings
Importance of feature scaling for regression models.

How to split and preprocess data properly.

How to evaluate regression models using common metrics.

Understanding model interpretability via coefficients.

## 📂 File Structure
California_Housing_Regression/
│
├── California_housing.ipynb       
├── california_housing.csv         
└── README.md                      #
