# ML_LR_Implemenation
This project is part of the Zero to Data Science Bootcamp by Jovian. It walks through applying Linear Regression on a real-world dataset to estimate annual medical charges using patient features like age, BMI, smoking status, and more.

📌 Problem Statement
ACME Insurance Inc. wants to estimate the annual medical expenditure for new customers using features such as:

Age
Sex
BMI (Body Mass Index)
Number of children
Smoking status
Region
These predictions help in determining insurance premiums and must be explainable due to regulatory requirements.

📊 Dataset
Source: stedy/Machine-Learning-with-R-datasets
Format: CSV
Rows: 1338
Columns: 7
No missing values

🔍 Key Features
Exploratory Data Analysis using Seaborn, Matplotlib, and Plotly
Correlation analysis and visualizations
Simple and multiple linear regression models
Use of categorical features with encoding (smoker, sex, region)
Evaluation using RMSE (Root Mean Squared Error)
Comparison of:
  Models with single vs. multiple features
  Separate models for smokers and non-smokers
  Effect of including categorical variables

✅ What You’ll Learn
How to clean and prepare data for machine learning
How to build and visualize linear regression models
How to handle categorical features in regression
How to evaluate model performance (RMSE, predictions)
When and why to split data into subgroups (e.g. smoker vs. non-smoker)


🛠️ How to Run
Clone this repo.
Open the notebook on Jupyter, Colab, or Binder.
Install dependencies.
Run the notebook cell by cell.


📈 Example Output
Model trained on:
- Non-smokers: RMSE ~ 4600
- Smokers: RMSE ~ 5700
- Combined Model: RMSE ~ 11,000
Adding smoker column as a feature drops combined model RMSE to ~6000

🙌 Acknowledgements
Tutorial by Jovian
Dataset from stedy/Machine-Learning-with-R-datasets
