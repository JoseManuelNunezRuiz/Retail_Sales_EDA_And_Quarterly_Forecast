## Retail Sales Dataset Analysis + Forecast

### Introduction
This project focuses on analyzing a retail sales dataset to derive insights and forecast future sales trends. The dataset includes information such as transaction details, customer demographics, product categories, and sales figures.

### Data Extraction and Preparation
The project starts with downloading and extracting the dataset from Kaggle, followed by loading the data into a DataFrame using Pandas. Data cleaning steps involve removing duplicates, renaming columns, and converting data types for analysis.

### Exploratory Data Analysis (EDA)
The EDA phase includes:
- Descriptive statistics to understand the dataset's characteristics.
- Calculating average and total sales by product category.
- Analyzing monthly total sales trends.
- Visualizing age distribution, sales by product category, and gender.
- Exploring total sales timeline and price distribution.

### Data Visualization
Various visualizations are created using Matplotlib and Seaborn to represent sales data, age distribution, product category insights, and correlation analysis between variables.

### Forecasting with Prophet
Utilizing the Prophet library, quarterly and monthly sales forecasts are generated for each product category. The forecasts provide insights into future sales trends based on historical data.

### Quarterly Forecast Results

- **Clothing:**
  - January: 14898.77
  - February: 14585.23
  - March: 13808.68
  - Total (Q) Clothing: 43292.68

- **Beauty:**
  - January: 12319.75
  - February: 11903.99
  - March: 12581.34
  - Total (Q) Beauty: 36805.08

- **Electronics:**
  - January: 13627.92
  - February: 13122.86
  - March: 14145.07
  - Total (Q) Electronics: 40895.85

### Conclusion
The project concludes with a comprehensive analysis of the retail sales dataset, forecasting trends, and visualizing key insights for informed decision-making.

For more details, refer to the code snippets and visualizations included in this repository.
