# House_Price_Prediction_LinearRegression

🧠 Task 3: Linear Regression

🎯 Objective:

-> To implement and understand both Simple and Multiple Linear Regression techniques for predicting continuous variables and interpreting model performance.

🛠️ Tools Used:

-> Tool	Description
  1. Pandas	For loading, cleaning, and manipulating tabular data
     
  2. Scikit-learn	For implementing linear regression models and evaluation metrics
     
  3. Matplotlib / Seaborn	For visualizing data distribution and regression lines

📝 Steps Followed (Mini Guide):

1.Import and Preprocess Dataset

-> Loaded the dataset using pandas.read_csv()

-> Cleaned missing values, converted categorical features using one-hot encoding

-> Feature selection based on correlation or domain knowledge

2.Split Data

-> Used train_test_split() from sklearn.model_selection to divide data into training and testing sets (typically 80-20 or 70-30 split)

3.Fit Linear Regression Model

-> Imported LinearRegression from sklearn.linear_model

-> Trained model using .fit(X_train, y_train)

-> Predicted using .predict(X_test)

4.Evaluate Model

-> Used:

   1. MAE (Mean Absolute Error)

   2. MSE (Mean Squared Error)

   3. R² Score to measure model accuracy

-> Printed metrics for comparison across models

5.Plot Regression Line

-> For simple regression, plotted actual vs predicted points and regression line using matplotlib.pyplot

-> Interpreted slope (coefficient) and intercept to understand feature impact

OUTPUT:

![Image](https://github.com/user-attachments/assets/ea3224d8-e04a-45a1-a405-ee66062823bd)
