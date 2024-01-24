**Sales insights data analysis project using power BI**

AtliQ Hardware company
AtliQ Hardware is a company which supplies computer hardware and peripherals to many of clients such as Excel stores, Surge stories across India. AtliQ Hardware head office is situated in Delhi, India and they have many regional offices throughout India.
Business challenges
The Sales Director faces significant challenges in tracking and understanding the dynamics of a rapidly growing market. The overall sales of the business have been on a decline, and the lack of concrete data and insights is hindering strategic decision-making. Communication with regional managers is primarily verbal, leading to a lack of documented evidence of the impact of market dynamics on the business. The verbal exchange of insights with regional managers has proven to be insufficient for gaining a comprehensive understanding of the business situation.
Solution:
Given the substantial scale of AtliQ hardware's business, there is a pressing need for a centralized and visualized dashboard. Such a dashboard would offer real-time, data-driven insights, enabling the Sales Director to make informed decisions and devise strategies to reverse the decline in sales effectively.
I used SQL queries in MYSQL Workbench to investigate the data and PowerBI for ETL and visualizations to create the insights.

1.Project planning with AIMS Grid and Data Discovery:

AIMS Grid -is a project management tool and it has four component-
Purpose- What do we want to do exactly. To unlock sales insights that are not visible before for sales team for decision support & automate them to reduced manual time spent in data gathering.
Stakeholders- People who will involve in the project– Sales Director, marketing team, Customer service team, Data Analytics team, and IT
End Result- – What do we want to achieve. An automated dashboard providing quick and latest sales insights to support data driven decision making
Success Criteria-Specifying the success of project.  
-Dashboard uncovering sales order insights with latest data available
-Sales team able to take better decisions & prove 10% cost savings of total spend
-Sales Analysts stop data gathering manually to save 20% of their business time and reinvest it value added activity

2.Data Exploration Using MySQL

Conduct an in-depth data analysis in SQL, revealing intricate insights within the dataset by running SQL queries on MYSQL database.
Overview
After a quick data exploration in MySQL, here are some initial findings:
-Total 150,000 records
-The database contains 5 tables: customers, date, markets, products, and transactions
-There are 17 markets, 279 products, and 38 customers
-The observation period is from January 2018 to June 2020
-The total revenue in 2020 was $ 142,23 M, 42% less than 2019, which was $ 336,45 M
-Most of the transactions data are in INR currency, but we have 4 records in US currency, so we need to convert it into INR as we are targeting India customers 

3. Data Cleaning and ETL

Next step is to pull data from MYSQL into Power BI and perform Data Cleaning known as ETL(Extract Transform and Load) to convert into different format so that we can perform Data Analysis in Power BI. Rigorous ETL processes and data cleaning enhanced the imported dataset’s integrity.

Dashboard includes-
•	Addressing currency disparities in transactions through meticulous conversion.
•	Key measures were meticulously developed and utilized to craft informative Power BI visuals
•	Revenue trends
•	Sales Quantity analysis
•	Revenue Breakdown by Markets
•	Sales Quantity Segmented by Markets
•	Revenue trends analyzed by Month & Year
•	Identification of Top 5 Products
•	Recognition of Top 5 Customers

Key Insights:

✨ In this dashboard, we can see company has generated total revenue of 985M, total profit margin ₹24.7M, Profit margin% 2.5%, Sales Qty ₹2M.
If we consider the insights for only 2020, company has generated total revenue of ₹ 142.5M by selling a total of 350K and earned a profit of ₹ 2.1M.

✨ In 4 years, Delhi is our largest market in terms of revenue with ₹ 520M but if you look at the profit margin Delhi is generating only 2.3% profit margin.

✨ If we check the profit margin then here in 2020, Bhubaneshwar comes into the picture which is generating the highest profit margin of 10.48%.

✨ In 4 years, Bengaluru generating the lowest profit margin of -20.8% and if we check the Profit % by Market then here also Bengaluru is the lowest with -0.3% of total contribution in total profit.

✨ In our top 5 customers, the Electricalsara Stores is our biggest customer who has generated total revenue of 413M, out of which we had a profit of 9M.

✨ In our top 5 products, the Prod040 is our highest product has generated total ₹ 23.5M revenue generated in 4 years.

✨ Revenue Trend is showing that in June 2020 revenue has been decreased drastically compared to the revenue last year and the profit margin was the least in April 2020. Sales director will come to know in which region sales are high and sales are low so that they can work on the product and enhance their business in this dynamically growth market



