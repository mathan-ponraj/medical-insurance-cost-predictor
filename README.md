# Medical Insurance Premium Prediction

## Project Overview
This project is a regression analysis task where I built a model to predict annual medical insurance premiums. By analyzing customer data like age, health metrics, and lifestyle choices, the system estimates the expected insurance cost for an individual.

## The Problem
Insurance companies need to set fair and accurate prices for their customers. The goal of this project is to understand how different factors—such as smoking habits or BMI—impact the final cost, allowing for data-driven pricing instead of manual estimation.

## My Technical Workflow

1. Data Exploration: I performed Exploratory Data Analysis (EDA) to find correlations between user habits (like smoking) and their total medical charges.
2. Data Preprocessing: I handled categorical data (like region and gender) using encoding techniques so the mathematical model could process them correctly.
3. Model Training: I split the data into 80% training and 20% testing sets. I applied Linear Regression to find the best-fit relationship between the customer features and the cost.
4. Evaluation: I used the R² score to measure how well the model's predictions matched the actual historical costs in the dataset.

## Results and Performance
The model provided a solid baseline for cost estimation:
- Training R² Score: Approximately 0.75
- Test R² Score: Approximately 0.74

Since the training and test scores are nearly identical, it shows the model is stable and generalizes well to new customers without being biased toward the training data.

## Tools Used
- Programming: Python
- Data Analysis: Pandas and NumPy
- Visualization: Matplotlib and Seaborn
- Machine Learning: Scikit-learn
- Environment: Jupyter Notebook

## Future Goals
To make the predictions even more accurate, I plan to:
- Use Gradient Boosting models like XGBoost to capture non-linear relationships.
- Apply Regularization (Ridge/Lasso) to prevent any single feature from dominating the model.
- Include error metrics like Mean Absolute Error (MAE) to understand the average rupee-value difference in predictions.

---
Developed by Mathan Ponraj
CSE Graduate | Data Science and Analytics
[LinkedIn Profile](https://www.linkedin.com)
