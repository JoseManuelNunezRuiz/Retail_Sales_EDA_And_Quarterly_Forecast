# Retail Sales Dataset Analysis And Forecast

## Project Overview
This project focuses on analyzing a retail sales dataset to derive insights and forecast future sales trends. The dataset includes information such as transaction details, customer demographics, product categories, and sales figures.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Extraction and Preparation](#data-extraction-and-preparation)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Data Visualization](#data-visualization)
5. [Forecasting with Prophet](#forecasting-with-prophet)
6. [Quarterly Forecast Results](#quarterly-forecast-results)
7. [Conclusion](#conclusion)

## Data Extraction and Preparation
The project starts with downloading and extracting the dataset from Kaggle, followed by loading the data into a DataFrame using Pandas. Data cleaning steps involve removing duplicates, renaming columns, and converting data types for analysis.

## Exploratory Data Analysis (EDA)
The EDA phase includes:
- Descriptive statistics to understand the dataset's characteristics.
- Calculating average and total sales by product category.
- Analyzing monthly total sales trends.
- Visualizing age distribution, sales by product category, and gender.
- Exploring total sales timeline and price distribution.

## Data Visualization
Various visualizations are created using Matplotlib and Seaborn to represent sales data, age distribution, product category insights, and correlation analysis between variables.

## Forecasting with Prophet
Utilizing the Prophet library, quarterly and monthly sales forecasts are generated for each product category. The forecasts provide insights into future sales trends based on historical data.

## Quarterly Forecast Results

- **Clothing:**
  - January: 14,898.77
  - February: 14,585.23
  - March: 13,808.68
  - **Total (Q) Clothing:** 43,292.68

- **Beauty:**
  - January: 12,319.75
  - February: 11,903.99
  - March: 12,581.34
  - **Total (Q) Beauty:** 36,805.08

- **Electronics:**
  - January: 13,627.92
  - February: 13,122.86
  - March: 14,145.07
  - **Total (Q) Electronics:** 40,895.85

## Conclusion

The Retail Sales Dataset Analysis + Forecast project provided valuable insights into sales trends, customer demographics, and product performance. Through rigorous data cleaning, exploration, and visualization, key patterns were identified, such as the significant contribution of specific product categories to overall sales and the seasonal variations in customer purchasing behavior.

The use of the Prophet library for forecasting demonstrated the potential future sales trends across different product categories. The analysis highlighted the need for targeted marketing strategies and inventory planning to optimize sales performance.

Overall, this project underscores the importance of data-driven decision-making in retail management. By leveraging detailed data analysis and forecasting techniques, businesses can better anticipate market demand, improve customer satisfaction, and drive profitability. The methodologies and findings from this analysis can serve as a foundation for further research and more sophisticated predictive modeling efforts.
