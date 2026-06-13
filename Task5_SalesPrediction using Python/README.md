<h1 align="center" style="font-size: 42px;">Task 5: Sales Prediction using Python </h1>

<h2 style="font-size: 28px;"> Objective</h2>

Predict the sales of a product based on advertising spend across different platforms (TV, Radio, Newspaper) using machine learning.

<h2 style="font-size: 28px;">Description</h2>

Sales prediction helps businesses understand how much of a product customers are likely to buy based on advertising expenditure and the platform used. This project builds a regression model to forecast sales figures, helping guide future advertising strategy.

<h2 style="font-size: 28px;">Tools & Libraries</h2>

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

<h2 style="font-size: 28px;"> Approach</h2>

1. **Data Loading & Cleaning** – Load the dataset and check for missing/duplicate values.
2. **Exploratory Data Analysis (EDA)**
   - Analyze relationship between advertising spend (TV, Radio, Newspaper) and Sales
   - Visualize correlations using scatter plots and heatmaps
3. **Model Building** – Train regression models such as:
   - Linear Regression
   - Random Forest Regressor
   - Decision Tree Regressor
4. **Model Evaluation** – Evaluate using R² score, MAE, and RMSE.
5. **Conclusion** – Determine which advertising medium has the highest impact on sales.

<h2 style="font-size: 28px;"> Dataset</h2>

- Source: Link provided in the OIBSIP task list (Advertising dataset, Kaggle).

<h2 style="font-size: 28px;"> Results</h2>

- Best model: `<model name>` with R² score of **X.XX**
- Add a chart showing actual vs predicted sales.

<h2 style="font-size: 28px;"> How to Run</h2>

```bash
pip install -r requirements.txt
jupyter notebook sales_prediction.ipynb
```

