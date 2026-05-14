# Credit Card Weekly Analysis
## Project Overview
I built two interactive Power BI dashboards to get a clear look at who's using credit cards and how they’re actually spending their money. By digging into demographics, income, and spending habits, I turned raw data into stories that show exactly how customers behave

The dashboards were designed as part of a Power BI analytics project to demonstrate data modeling, DAX calculations, and dashboard storytelling skills.

Dashboards Included
- Customer Report Dashboard
- Focuses on customer demographics, segmentation, and satisfaction metrics.
- Transaction Report Dashboard
- Focuses on revenue, transaction patterns, and week-over-week (WoW) performance.

## Objectives
- To visualize key customer metrics such as demographics, income, and card usage.
- To analyze transaction trends by expenditure type, week, and card category.
- To enable interactive exploration through filters and slicers for:
  - Gender
  - Age Group
  - Income Group
  - Card Category
  - Transaction Week
  - Expense Type

## Data Modeling & Transformations
- Performed data cleaning and transformation in Power Query.
- Created a relationship between customer and transaction datasets using Customer_ID as the primary key.
- created a datetable and link it to the transaction dataset
- Created calculated columns and measures using DAX, including:
  - Age Group
  - Income Group
  - Total Revenue
  - Credit Usage %
  - Week Number
  - Current Week Revenue
  - Previous Week Revenue
  - WoW Growth %

## Key DAX Calculations
- Age Group segmentation
- Income Group classification (Low, Medium, High)
- Total Revenue and Transaction Metrics
- Current Week Revenue
- Previous Week Revenue (dynamic handling of missing weeks)
- Week-over-Week (WoW) Change and Percentage

## Interactivity
Implemented dynamic filtering using slicers:
- Gender
- Age Group
- Income Group
- Card Category
- Week Number

Customer Analysis Dashboard
Purpose: Understand customer distribution, income segmentation, and card preferences.

Key Metrics:

Total Customers
Total Revenue
Active Card Holders
Average Credit Limit
Average Credit Score
Key Visuals:

Total Customers by Age Group
Total Customers by Gender
Total Revenue by Gender
Average Income by Customer_Job
Average Credit Limit by Income Group
Total Customers by Education Level
Total Customers by Age Group and Gender
Total Customers by Card Category
Insights:

Majority of customers are aged 36–55, with females (58%) dominating the user base.
Blue cards are the most common category among customers.
Businessmen and White-collar professionals earn the highest average income.
High-income customers enjoy higher credit limits (~14K).
Credit Card Transaction & Revenue Dashboard
Purpose: Analyze revenue generation, spending categories, and transaction frequency trends.

Key Metrics:

Total Revenue
Total Transactions
Average Transaction
Growth Percentage
Key Visuals:

Total Revenue by Month
Average Utilization Ratio
Total Transaction by use chip
Total Revenue by Exp Type
Sum of Total Transaciton Amount by Card Category
Insights:

Blue Card customers generate nearly 89% of total transactions.
Bills, Entertainment, and Fuel** are the top spending categories.
Online transactions are steadily increasing.
Male customers contribute slightly higher total revenue, while female customers have a higher average income per transaction.
Recommendations
Reward the most active users.
Grow the premium user base.
Partner with top categories.
Boost female spending.
Promote online transactions.
Target high earners.
Fix spending dips.
Results
Built two fully interactive, visually clean Power BI dashboards.
Improved understanding of data modeling, DAX, and Power BI storytelling.
Learned how to create insight-driven visuals for business intelligence use cases

## Challenges & Solutions
Drill-through Implementation
Challenge: Drill-through was not initially working due to the missing Client_Num in the main visuals.
Solution: Integrated Client_Num into visuals to enable proper context transfer and filtering.
Learning: Improved understanding of Power BI filter context and interaction behavior.

## Dashboard Overview
![Dashboard Preview](https://github.com/amieecode/credit-card-weekly-status-analysis/blob/main/Image/credit%20card.png)

![Dashboard Preview](https://github.com/amieecode/credit-card-weekly-status-analysis/blob/main/Image/credit%20card%202.png)

### Contact
Feel free to connect or provide feedback!
