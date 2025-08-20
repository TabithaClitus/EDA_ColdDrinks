Cold Drink Sales Prediction:

This project builds a simple linear regression model to predict cold drink sales based on temperature. The dataset comes from a supermarket that collected sales information along with environmental and business-related factors. For this task, we focus on the relationship between temperature (°C) and sales.

📊 Problem Statement

A supermarket wants to understand how temperature affects cold drink sales. Using regression analysis, we aim to:

Train a model that predicts sales from temperature.

Estimate sales on a 40°C day.

Analyze residuals to check whether the model performs equally well across all temperature ranges.

🧮 Methodology

Step 1: Load and explore the dataset.

Step 2: Select Temperature_C as the feature (X) and Sales as the target (y).

Step 3: Train a Linear Regression model (sklearn.linear_model.LinearRegression).

Step 4: Predict sales for 40°C.

Step 5: Compute residuals (actual − predicted) and visualize them to assess model performance.

📈 Visualizations

Residuals vs Temperature → Checks if errors are randomly distributed.

✅ Results

The model predicts ~578 cold drinks sold at 40°C.

Residual analysis helps evaluate whether linear regression is a good fit or if more complex models.

<img width="560" height="413" alt="image" src="https://github.com/user-attachments/assets/f770843b-8008-4543-bb7d-b5049fa09ede" />

The scatter plot shows the relationship between temperature (°C) and cold drink sales.

Blue dots represent the actual sales data collected at different temperatures.

The red line is the regression line obtained from training a simple linear regression model, which estimates the general trend of sales with temperature.

The green "X" marker highlights the model’s prediction of sales at 40°C, which in this case is approximately 578 units.


