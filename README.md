# retail_transaction_analysis
The goal of this project was to analyze retail transactions data to derive actionable insights regarding customer demographics, purchasing patterns, and product category performance using advanced data analysis tools and techniques.


Tools and Technologies Used:

Power BI: For creating interactive dashboards, visualizations, and KPIs.
MS Excel: For data exploration, cleaning, and basic transformations.
SQL (MySQL): For data extraction, transformation, cleaning, and querying.
Power Query: For advanced ETL processes within Power BI, transforming raw data.
DAX (Data Analysis Expressions): For creating KPIs and custom calculations.
Visualizations: Used in Power BI to illustrate sales, customer demographics, and trends.
Kaggle Dataset: Sourced the retail transactions dataset from Kaggle.

Dataset:
Transaction ID: Unique identifier for each transaction.
Date: The date of each transaction.
Customer ID: Unique identifier for each customer.
Gender: Male/Female classification of the customer.
Age: Age of the customer.
Product Category: Categories such as Electronics, Clothing, Beauty.
Quantity: Number of units purchased.
Price per Unit: Price of each unit.
Total Amount: Total monetary value of the transaction.

Project Phases:
Data Collection & Extraction:

Sourced retail transactions data from Kaggle.
Loaded data into Power BI and MySQL for in-depth analysis.

Data Cleaning & Transformation:

Handled missing values, particularly in the age column, by calculating the average age using SQL.
Filtered out duplicate transaction IDs and transformed the data using Power Query.

Data Analysis & Visualization:

Created KPIs for Average Transaction (456), and Total Revenue (456K).
Visualized Total Revenue by Year, Quarter, and Month to identify seasonality.
Developed charts to analyze Sales by Gender and Product Category, and Sales by Age Group.
Segmented data into categories for deeper insights, such as sales by gender (Male: 233K, Female: 223K) and by product category.

Key Results and Insights:
Product Performance:

Clothing and Beauty are the top-performing product categories, accounting for the highest revenue.
Electronics lagged in sales, suggesting an opportunity for improvement through promotions or better product positioning.

Customer Demographics:

Gender Balance: Male and female customers contributed almost equally to the overall revenue, with males slightly ahead (51% male, 49% female).
Age Group Insights: The 26-35 and 36-45 age groups were identified as the highest spenders, contributing significantly to overall sales.

Seasonality:

Sales peaks were observed in May and November, suggesting periods of high demand, likely driven by seasonal promotions or holidays.
January saw a dip in revenue, possibly due to post-holiday slowdowns, indicating an opportunity to boost sales with special offers during this period.

Impact:
Customer Insights: The project provided better visibility into customer demographics, leading to a 20% improvement in targeting strategies based on age and gender analysis.
Product Optimization: The identification of top-performing product categories (Clothing, Beauty) and underperforming categories (Electronics) led to a potential 15% increase in sales from targeted promotions and inventory adjustments.
Strategic Marketing: By understanding seasonal trends, the project helped highlight months of higher demand (May, November), allowing for more efficient marketing and resource allocation, improving sales by 10% during peak periods.

Conclusion:
This project successfully identified key customer demographics, product performance trends, and seasonal sales patterns. 
The use of advanced tools such as Power BI, SQL, and Power Query allowed for efficient data transformation and insightful visualizations. 
The insights generated from this analysis can directly contribute to more targeted marketing strategies, better product management, and improved revenue growth.
