# DiwaliSalesAnalysis

This project provides an in-depth analysis of Diwali sales data, including customer demographics, purchasing behavior, and product preferences. The dataset is analyzed using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn.


**Objective**

The goal of this project is to analyze sales data during the Diwali festival to uncover key patterns and insights regarding customer behavior, product preferences, and other factors that influence purchasing decisions. The analysis aims to answer questions such as:

Who are the most frequent buyers based on demographics?
Which product categories are most popular?
What factors (e.g., age, gender, marital status, occupation) influence purchase behavior?

**Dataset**

The dataset contains 11,251 entries and 15 columns with details on customer information, orders, and product categories. Key columns include:

User_ID, Cust_name, Gender, Age Group, Age, Marital_Status, State, Occupation, Product_Category, Orders, Amount
Steps Involved

**Data Cleaning and Preprocessing:**

Removed irrelevant or blank columns (Status, unnamed1).
Dropped missing values (12 records with null Amount).
Changed data types (converted Amount to integer).
Renamed columns for clarity.

**Exploratory Data Analysis (EDA):**

Visualized the distribution of sales across different gender, age groups, states, marital status, occupations, and product categories.
Identified top-selling products and regions with the highest sales.

**Key Insights:**

Most of the buyers are females in the age group of 26-35 years.
Top-selling states include Uttar Pradesh, Maharashtra, and Karnataka.
Married women show higher purchasing power.
Popular product categories include Food, Clothing, and Electronics.
The most frequently purchased products are in the Food and Electronics categories.

**Key Visualizations**

Bar plots for gender-wise sales, age group-wise sales, and occupation-wise sales.
Top-selling states and product categories visualized using bar charts.
Product popularity based on the number of orders.

**Conclusion**

The analysis reveals that married women, particularly in the age group of 26-35 years, from Uttar Pradesh, Maharashtra, and Karnataka, working in sectors like IT, Healthcare, and Aviation, are more likely to buy products in the Food, Clothing, and Electronics categories.
