# Score Prediction Notebook

This Jupyter Notebook is designed to predict scores based on the number of study hours using a linear regression model. The notebook covers the entire data analysis pipeline, including data loading, preprocessing, exploratory data analysis, model training, and evaluation.

## Contents

1. **Introduction**
   - The notebook's objective is to understand the grades (percentage) of students who studies 9.5 hours a day..

2. **Data Loading and Preprocessing**
   - Import necessary libraries (`pandas`, `numpy`, `matplotlib`, `sklearn`).
   - Load the dataset from a given URL.
   - Display the first few rows of the dataset to ensure it is loaded correctly.

3. **Exploratory Data Analysis (EDA)**
   - Visualize the relationship between study hours and scores using scatter plots.
   - Understand the distribution and summary statistics of the data.

4. **Data Splitting**
   - Split the dataset into training and testing sets to validate the model's performance.

5. **Model Training**
   - Train a linear regression model using the training data.
   - Fit the model to the data and print the regression coefficients.

6. **Model Evaluation**
   - Evaluate the model's performance using the testing data.
   - Calculate and print the Mean Absolute Error (MAE) to assess prediction accuracy.

7. **Visualization of Predictions**
   - Plot the regression line along with the data points to visualize the model's fit.
   - Predicted the grade (percentage) as 94% if the student studies 9.5 hours a day
