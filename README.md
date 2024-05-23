**Video Game Sales Analysis and Prediction**	
  This project involves analyzing video game sales data and predicting global sales using various regression models, including Linear Regression, Polynomial Regression, Lasso Regression, and Ridge Regression. The dataset used is vgsales.csv.

**Project Workflow**

**Data Loading and Preprocessing:**
	Loaded the dataset and checked for missing values.
	Performed data cleaning by removing rows with missing values.
	Applied label encoding to categorical features for numerical transformation.
 
**Exploratory Data Analysis (EDA):**
	Analyzed the dataset's structure and unique values.
	Examined correlations between different features.
 
**Feature Engineering:**
	Dropped irrelevant columns such as 'Rank', 'Name', 'Platform', 'Year', 'Genre', and 'Publisher' to focus on sales data.
 
**Model Training:**
	Split the dataset into training and testing sets.
	Trained four regression models: Linear Regression, Polynomial Regression (degree=2), Lasso Regression, and Ridge Regression.
 
**Model Evaluation:**
	Evaluated the performance of each model using various metrics: Mean Squared Error (MSE), R-Squared (R2), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE).
	Compiled the evaluation metrics into a comprehensive table for comparison.
 
**Sales Prediction:**
	Provided a user input interface to predict global sales based on North America, Europe, Japan, and other sales regions using the trained models.
 
**Results**
	The performance of each regression model was evaluated and compared based on key metrics:
	Linear Regression
	Polynomial Regression
	Lasso Regression
	Ridge Regression
