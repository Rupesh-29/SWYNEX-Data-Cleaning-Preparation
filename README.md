# SWYNEX-Data-Cleaning-Preparation
Sales Transactions 2022–2025 — Cleaned Dataset

📊 Project Overview

This dataset contains cleaned sales transaction records covering the period 2022 to 2025. The data includes customer information, order details, product information, sales and profit metrics, payment details, shipping information, returns, promotions, and inventory-related fields.

The purpose of this cleaning process was to improve the quality, consistency, and usability of the dataset for further analysis, reporting, visualization, and dashboard creation.

📁 Dataset Details

Dataset: Sales Transactions 2022–2025

Rows: 18,000

Columns: 36

Time Period: 2022–2025

Data Status: Cleaned and ready for analysis

File: Sales_transactions_2022_2025 (After Cleaning).xlsx

🧹 Data Cleaning Performed

1. Removed Duplicate Values

Duplicate records were identified and removed from the entire dataset.

This ensures that:

Each transaction is represented only once.

Duplicate records do not affect sales and profit calculations.

Aggregations and dashboard results are more reliable.

The dataset is suitable for further analysis.

After cleaning, there are no duplicate rows in the dataset.

2. Handled Missing Values and Data Types

Missing values and inconsistent data types were reviewed and handled during the cleaning process.

The following areas were checked:

Customer information

Customer age and rating

Product information

Payment details

Delivery information

Return information

Promotion codes

Inventory levels

Date and time fields

Numerical sales and profit fields

Data types were also reviewed to make sure that numerical, date, time, and text-based columns are stored in appropriate formats for analysis.

Note: Some fields can legitimately remain blank after cleaning. For example, Return_Reason may be blank when an order was not returned, and Promotion_Code may be blank when no promotion was applied.

3. Standardized the City Column

The City column was standardized so that each word begins with a capital letter.

For example:

los angeles → Los Angeles

new york → New York

sydney → Sydney

This improves consistency and makes the data easier to read, group, filter, and visualize.

🗂️ Main Columns

The dataset contains the following major categories of information:

Customer Information

Customer_ID

Customer_Name

Customer_Age

Customer_Gender

Customer_Segment

Order Information

Transaction_ID

Order_ID

Order_Date

Order_Time

Sales_Channel

Order_Status

Store & Location Information

Store_ID

Store_Name

Country

Region

City

Product Information

Product_ID

Product_Name

Product_Category

Product_Subcategory

Sales & Financial Information

Quantity

Unit_Price

Discount_Percentage

Sales_Amount

Cost_Amount

Profit

Payment, Shipping & Returns

Payment_Method

Shipping_Method

Delivery_Days

Return_Flag

Return_Reason

Additional Information

Sales_Representative

Promotion_Code

Customer_Rating

Inventory_Level

Order_Year

🔍 Data Quality Checks

The cleaned dataset was checked for:

Duplicate rows

Missing values

Appropriate data types

Consistent city-name formatting

Numerical field consistency

Date and time formatting

Text field consistency

🎯 Purpose of the Cleaned Dataset

The cleaned dataset can be used for:

Exploratory Data Analysis (EDA)

Sales performance analysis

Customer analysis

Product performance analysis

Profitability analysis

Regional and city-level analysis

Sales channel analysis

Return analysis

Promotion analysis

Inventory analysis

Power BI dashboards

Excel dashboards

SQL practice and analysis

Python-based data analysis

🛠️ Tools Used

Microsoft Excel — Data cleaning and transformation

SQL — Data analysis and querying

Power BI — Dashboard and visualization

✅ Final Status

The dataset has been cleaned and standardized and is ready for the next stage of the project: data analysis, visualization, and dashboard development.
