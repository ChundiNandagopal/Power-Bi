# Medicine Sales Analysis Dashboard STY 05


## Project Objective

The primary objective of this project is to develop a comprehensive and visually appealing Power BI dashboard that analyzes the medicine sales data for the entire year of 2023 and 2022.

This initiative has been undertaken in response to stakeholders' requests to gain a clear understanding of sales performance. By transforming raw data into actionable insights, the dashboard aims to assist stakeholders in making informed strategic decisions for future planning.

#

## Dataset Overview
This project involves analyzing medicine sales data using **three provided CSV files**. Each file represents a different aspect of the dataset: **customers**, **drugs**, and **sales transactions**. 


Below is a detailed description of each table, including the data types and brief descriptions of each column.

### 1. Customer Table
The Customer Table contains information about the customers who purchase medicines.

|Column	| Data Type	|Description|
|--|--|--|
|CustomerID|	Integer	|Unique identifier for each customer|
|FirstName|	String|	First name of the customer|
|LastName	|String	|Last name of the customer|
|Age	|Integer	|Age of the customer|
|Gender|	String|	Gender of the customer|
|Country|	String|	Country where the customer resides|
|OtherCustomerInfo|	String	|Additional information about the customer (e.g., Frequent Buyer, New Customer)|

### 2. Drugs Lookup Table
The Drugs Lookup Table contains information about the medicines available for sale.

|Column	|Data Type|	Description|
|--|--|--|
|DrugID	|Integer	|Unique identifier for each drug|
|RegulatoryComplianceID	|Integer	|Identifier for regulatory compliance category|
|DrugName	|String|	Name of the drug|
|UnitSalesPrice	|Float|	Sales price per unit of the drug|
|CostOfProduction	|Float	|Production cost per unit of the drug|
|Treats	|String	|Description of what the drug treats|

### 3. Sales Transactions Table
The Sales Transactions Table records each sale made, including details of the drug sold and the customer who bought it.

|Column|	Data Type	|Description|
|--|--|--|
|SaleID	|Integer|	Unique identifier for each sale|
|DrugID|	Integer	|Identifier for the drug sold|
|CustomerID|	Integer	|Identifier for the customer who bought the drug|
|UnitsSold	|Integer	|Number of units sold in the transaction|
|SaleDate|	Date	|Date of the sale|
|BuyerType	|String	|Type of buyer (e.g., Seller, User)|

### Summary
 * **Customer Table**: Provides demographic and additional information about each customer.
 * **Drugs Lookup Table**: Contains details about each drug, including pricing and regulatory information.
 * ***Sales Transactions Table**: Records details of each sale, including the drug sold, the customer, and the transaction specifics.

#

## Dashboard Overview
Based on the project objective, I have developed a single page Power BI dashboard report to analyze and visualize the medicine sales data for 2023. The dashboard is structured as follows:


#

Lets dive into detailed explanations:

# Detailed Insights Explanation:

## Page-One: Home

![Image](https://github.com/ChundiNandagopal/Power-Bi/blob/main/Medicine%20Sales%20Analysis/msr.jpg)


This page has been designed to be visually appealing, aiming to provide a comprehensive summary of overall sales performance. The dashboard effectively uses various visual elements to present key performance indicators (KPIs) and other relevant data points.

### Top KPIs:
 * Total Quantity Sold: 245k units
 * Total Cost of Goods Sold (COGS): $11.69 million
 * Total Revenue: $65 million
 * Profit: $53 million

### Revenue by Drug Name:
 * A bar chart is used to display revenue generated by each drug. It shows that Lisinopril has the highest revenue at $3.2 million.

 * Users can also view drugs based on **COGS**, **quantity sold**, and **profit** by clicking the respective buttons provided.

### Revenue by Customer:
 * Another bar chart illustrates revenue generated by each customer. Analysis reveals that David Johnson is the top revenue-generating customer, contributing $3.6 million.

 * Users can also view customer data based on **quantity sold** and **profit** by clicking the appropriate buttons.

### Profit by Buyer Type:
 * A doughnut chart is used to depict profit distribution by buyer type. It shows that sellers generate the highest profit at $46.49 million, which is 87.75% of the total. In contrast, users contribute $6.49 million, accounting for 12.25% of the total profit.

 * Users can switch the view to see **total revenue** or **quantity** by buyer type by clicking the respective buttons.

This overview page provides a high-level snapshot of the sales data, enabling stakeholders to quickly grasp key metrics and performance indicators. The interactive elements allow for deeper exploration and understanding of the data based on specific criteria.


#
### Top KPIs Section:
Important KPIs are displayed at the top of the page to give a quick overview of customer metrics:
 * Total Customers: 200
 * Average Revenue per Customer: $323,000
 * Total Transactions: 15,000
 * Average Revenue per Transaction: $4,200
 * These KPIs provide a snapshot of customer engagement and financial performance.

### Sales by Country:
A map chart is used to visualize sales by country. Users can also switch to a chart view if preferred.

Analysis reveals that the **highest revenue is generated from Canada at $29 million**, followed by:
 * Australia: $12 million
 * Germany: $6 million
 * United Kingdom: $6 million
 * United States: $5 million
 * France: $5 million **(lowest)**

### Revenue by Gender:
A bar chart displays revenue by gender.

Analysis indicates that the **highest revenue is generated from males at $30 million**, followed by:
 * Females: $21 million
 * Others: $12 million (lowest)

### Revenue by Age Group:
A bar chart is used to show revenue by age group.

Analysis shows that the **highest revenue is generated from the 51+ age group at $34 million**, followed by:
 * 31-40 age group: $11 million
 * 41-50 age group: $9 million
 * 21-30 age group: $8 million
 * 0-20 age group: $3 million (lowest)

### Revenue by Year:
 * A line chart displays revenue by year.
 * Analysis shows revenue of $**3 million in 2022** and **$62 million in 2023**, indicating significant growth.

### Revenue by Quarter:
Analysis indicates revenue as follows:
 * Q1: $15.86 million
 * Q2: $15.35 million
 * Q3: $16.40 million
 * Q4: $16.06 million

### Revenue by Month:
Analysis reveals that the **highest revenue is generated in July**, while the **lowest is in August**.

### Revenue by Day Name:
 * The purpose of this chart is to show revenue based on the day of the week.
 * Analysis shows that the **highest revenue is generated on** **Fridays at $9.8 million**, while the **lowest is on Thursdays at $8.6 million.**

This page provides a comprehensive view of customer demographics, sales performance by geography, and temporal trends, allowing stakeholders to make informed decisions based on detailed customer and sales insights.

#

## Real-World Recommendations Based on Insights
Based on the detailed insights from the Power BI dashboard analyzing the medicine sales data for 2023, here are the top five recommendations for stakeholders to consider:

 * **Focus marketing efforts on Lisinopril:**  The data shows Lisinopril is the top revenue generator.  Allocate marketing budget to promote this drug and potentially explore upselling or cross-selling related medications.

 * **Target high-value customers like David Johnson:**  Identify and target high-revenue customers like David Johnson with personalized marketing campaigns and loyalty programs to retain their business and potentially increase their purchases.

 * **Increase sales to female and younger demographics:**  The data suggests lower sales from females and younger age groups. Develop targeted marketing campaigns to reach these demographics and understand their specific needs and preferences.

 * **Expand sales in high-revenue countries**:  Canada leads in sales, followed by Australia, Germany, and the UK. Consider regional marketing campaigns or explore partnerships with distributors in these countries to further increase sales.

 * **Analyze seasonal trends and optimize promotions:**  Sales data indicates a peak in July and a dip in August.  Investigate reasons behind these trends and plan targeted promotions or discounts strategically to address seasonal fluctuations.

#

## My Learnings:
This project has significantly enhanced my analytical skills, particularly in using Power BI for data visualization and analysis. I am now more confident in my ability to transform raw data into meaningful insights that can drive strategic business decisions. This experience has prepared me well for future data analysis projects, and I look forward to applying these skills in more complex and challenging scenarios.

I hope scrolling through this project provides you with insightful understanding.

Thank you for taking the time to view my project.


### Created and Presented by-

Chundi Nanda Gopal Reddy

