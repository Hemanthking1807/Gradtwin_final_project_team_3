# Gradtwin_final_project_team_3
# FreshCart – Multi-Store Demand Forecasting with Deep Learning

## Project Overview

The FreshCart Multi-Store Demand Forecasting project aims to analyze historical supermarket sales data and predict future product demand across multiple stores using Machine Learning and Deep Learning techniques.

The project focuses on understanding sales patterns, identifying seasonal trends, analyzing store-wise and product-wise demand, and developing forecasting models to help supermarkets improve inventory management and make better purchasing decisions.

**Client:** FreshCart Supermarkets  
**Duration:** 8 Weeks  
**Team Size:** 3 Members  
**Project Domain:** Data Science, Machine Learning & Deep Learning

---

## Project Objectives

- Analyze historical sales data from multiple supermarkets.
- Understand daily, weekly, monthly, and yearly sales patterns.
- Identify high-demand and low-demand products (SKUs).
- Analyze the impact of festivals, holidays, and weather conditions on sales.
- Develop demand forecasting models using Machine Learning and Deep Learning.
- Compare forecasting models such as LightGBM and LSTM.
- Estimate future product demand and support inventory planning.
- Recommend appropriate order quantities to reduce overstocking and stockouts.

---

## Technologies & Tools Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Data preprocessing and ML |
| LightGBM | Machine Learning forecasting |
| TensorFlow/Keras | Deep Learning with LSTM |
| Jupyter Notebook | Development and experimentation |
| Git & GitHub | Version control and project management |

---

## Project Workflow

1. Data Collection and Understanding
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Machine Learning Model Development
6. Deep Learning Model Development
7. Model Evaluation and Comparison
8. Demand Prediction and Order Quantity Recommendations

---

# Weekly Progress

## Week 1 – Data Understanding & Exploratory Data Analysis (EDA)

### Objective

The main objective of Week 1 was to understand the sales dataset, examine its structure, identify data quality issues, and explore initial sales patterns before starting the forecasting process.

### Tasks Completed

**1. Dataset Understanding**
- Loaded the sales dataset using Pandas.
- Inspected dataset rows, columns, and data types.
- Examined important columns such as date, store, SKU, and quantity sold.
- Identified the minimum and maximum dates in the dataset.

**2. Data Quality Checks**
- Checked missing values in all columns.
- Identified duplicate records.
- Generated a continuous date range using `pd.date_range()`.
- Identified missing dates across the overall dataset.
- Explored the importance of checking missing dates separately for each Store-SKU combination.

**3. Exploratory Data Analysis**

Performed initial sales analysis to understand demand patterns.

- **Yearly Sales Analysis:** Calculated total quantities sold for each year and visualized the results using a bar chart.
- **Monthly Sales Analysis:** Examined monthly sales trends to identify high-demand and low-demand months.
- **Store-Wise Sales Analysis:** Compared total sales across different stores.
- **SKU-Wise Sales Analysis:** Identified the top-selling products based on total quantity sold.

### Python Concepts Practiced

- `pd.read_csv()`
- `df.info()`
- `df.describe()`
- `df.isnull().sum()`
- `df.duplicated().sum()`
- `pd.date_range()`
- `groupby()`
- `sum()`
- `sort_values()`
- `dt.year` and `dt.month`
- `plot()`

### Week 1 Outcomes

- Gained an understanding of the sales dataset and its structure.
- Identified potential data quality issues.
- Understood how to check missing dates and duplicate records.
- Analyzed yearly and monthly sales patterns.
- Compared sales performance across stores and products.
- Established a foundation for data preprocessing and demand forecasting.

---

## Upcoming Weekly Plan

| Week | Planned Activities |
|---|---|
| Week 1 | Data Understanding and EDA |
| Week 2 | Data Cleaning and Preprocessing |
| Week 3 | Feature Engineering and External Factors |
| Week 4 | Machine Learning Model Development (LightGBM) |
| Week 5 | Deep Learning Model Development (LSTM) |
| Week 6 | Model Evaluation and Comparison |
| Week 7 | Demand Forecasting and Order Quantity Optimization |
| Week 8 | Final Results, Documentation and Presentation |

---

## Expected Business Benefits

- Better inventory management.
- Reduced product overstocking.
- Fewer stockout situations.
- Improved demand prediction accuracy.
- Better purchasing and replenishment decisions.
- Improved supermarket operational efficiency.

---

## Team Members

1. G Hemanth Reddy
2. Naresh Muddan
3. M Mohamed Anas

---

## Project Status

**Current Status:** Week 1 – Data Understanding & EDA

This project is currently in its initial analysis stage. Further data preprocessing, feature engineering, model development, and evaluation will be carried out in the upcoming weeks.

---

*FreshCart Multi-Store Demand Forecasting with Deep Learning – 8 Week Data Science Project.*
