# Laptop-Price-Prediction-ML
Machine learning project for predicting laptop prices using regression models with EDA and evaluation metrics.

The objective of this project is to implement, analyze, and compare various Linear Regression models to predict laptop prices based on multiple hardware and software features.
This assignment helps in understanding Simple, Multiple, Polynomial, and Regularized Regression models along with proper evaluation and interpretation.

Dataset Description:-
The dataset contains specifications of laptops along with their prices.
It includes multiple input features and one continuous target variable.

Features Used:
Company,
TypeName,
Inches,
ScreenResolution,
CPU,
RAM,
Memory,
GPU,
Operating System,
Weight,

Target Variable:-
Price

The dataset satisfies the requirement of having multiple input features and a continuous output variable, as specified in the assignment.

Tools & Technologies
Python
Jupyter Notebook / Google Colab
Libraries used:
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn

Methodology

Part A: Exploratory Data Analysis (EDA):-
Loaded the dataset and examined its structure.
Generated summary statistics for numerical features.
Checked for missing values and handled unnecessary columns.
Visualized feature distributions.
Created a correlation heatmap to understand relationships between variables.

Part B: Simple Linear Regression :-
Selected a single feature (e.g., RAM or Inches).
Built a simple linear regression model.
Plotted the regression line.
Interpreted the slope and intercept.


Part C: Multiple Linear Regression:-
Used multiple features to predict laptop prices.
Trained a Multiple Linear Regression model.
Evaluated model performance using:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
Interpreted regression coefficients.


Part D: Polynomial Regression:-
Applied Polynomial Regression to capture non-linear relationships.
Compared Linear and Polynomial Regression results.
Observed improvement in prediction accuracy for non-linear patterns.


Part E: Regularization Techniques:-
Applied Ridge Regression and Lasso Regression.
Compared coefficients with linear regression.
Discussed feature selection and overfitting control.

Part F: Model Diagnostics:-
Plotted residuals vs predicted values.
Checked regression assumptions such as linearity and homoscedasticity.



Results & Observations:-
Multiple Linear Regression performed better than Simple Linear Regression.
Polynomial Regression captured non-linear relationships more effectively.
Ridge and Lasso regression helped in reducing overfitting.
RAM, CPU, and Storage were observed to be strong predictors of laptop price.

conclusion:-
This project provided hands-on experience with different linear regression models and demonstrated how regression techniques can be used for real-world price prediction problems.
The assignment improved understanding of model selection, evaluation, and interpretation, fulfilling all the objectives of the Linear Regression Lab. 
