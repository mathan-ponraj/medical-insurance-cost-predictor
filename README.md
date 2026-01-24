# Insurance Cost Prediction using Linear Regression

## Case Study

### Problem
Health insurance providers need accurate predictions of individual medical costs to support pricing, underwriting, and risk management decisions.

### Context
This project uses a real-world insurance dataset containing demographic, lifestyle, and regional features to predict annual insurance charges using supervised machine learning.

### Impact
- Built a regression model explaining ~75% of the variance in insurance costs
- Identified key cost drivers such as smoking status, BMI, and age

### Why It Matters
Accurate insurance cost estimation enables better pricing strategies, improved risk assessment, and more data-driven healthcare decisions.

---

## What I Did

- Performed end-to-end data analysis and regression modeling
- Conducted exploratory data analysis (EDA) on numerical and categorical features
- Preprocessed data and encoded categorical variables
- Trained and evaluated a Linear Regression model
- Validated model performance using R² score
- Implemented insurance cost prediction for new customer inputs

---

## How I Did It (STAR Method)

### Situation
The dataset contained mixed data types (numerical and categorical) influencing insurance charges.

### Task
Predict continuous insurance costs with an interpretable and reliable baseline model.

### Action
- Loaded and validated the dataset (null checks, data types, summary statistics)
- Visualized feature distributions using Matplotlib and Seaborn
- Encoded categorical variables (sex, smoker, region)
- Split data into training and testing sets (80/20)
- Trained a Linear Regression model using scikit-learn
- Evaluated model performance on training and test data using R² score

### Result
- Training R² score: ~0.75
- Test R² score: ~0.74
- Model generalized well with minimal overfitting
- Enabled prediction of insurance costs for unseen customer profiles

---

## Tech Stack

- **Programming Language:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Model:** Linear Regression
- **Evaluation Metric:** R² Score
- **Environment:** Jupyter Notebook

---

## Key Results / Business Impact

- Achieved strong baseline regression performance
- Demonstrated impact of lifestyle factors on insurance pricing
- Delivered an interpretable model suitable for business and policy analysis
- Established a foundation for advanced modeling (regularization, tree-based models)
