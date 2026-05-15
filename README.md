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

### Customer Analysis Dashboard

Purpose: Understand customer distribution and income segmentation.

#### Key Metrics:
- Total Customers
- Total Revenue
- Average Interest Earned
- Average Satisfaction Score

#### Key Visuals:
- Total Customers by Age Group
- Total Customers by Income Group
- Total Revenue by Gender
- Average Income by Customer_Job
- Total Customers by Education Level
- Total Customers by Personal Loan
- Total Customers by Marital Status
  
#### Insights:
- The majority of customers are aged 36–55, with females (58%) dominating the user base.
- Blue cards are the most common category among customers.
- Businessmen and White-collar professionals earn the highest average income.
- Graduates earn more, and a greater percentage of customers owe no Loan
- A greater portion of the customers own no care(53%) and mostly are low income earners 


### Credit Card Transaction & Revenue Dashboard

Purpose: Analyze revenue generation, spending categories, and transaction frequency trends.

#### Key Metrics:
- Total Revenue
- Total Transactions
- Total Interest Earned
- Average Credit Limit
- Growth Percentage

#### Key Visuals:
- Revenue Trend Over Time
- Total Revenue by Exp Type
- Credit Limit by income type
- Total Transaction by Card Usage
- Total Transaction Amount by Card Category
- Transaction Volume by Expense Type

#### Insights:
- Blue Card customers generate nearly 89% of total transactions.
- Bills, Entertainment, and Fuel** are the top spending categories.
- Online transactions are steadily increasing.
- Male customers contribute slightly higher total revenue, while female customers have a higher average income per transaction.
- High-income customers enjoy higher credit limits (~14K).
- Most of the customer use Swipe in their transaction 

### Recommendations
1. Reward the most active users.
2. Grow the premium user base.
3. Partner with top categories.
4. Boost female spending.
5. Promote online transactions.
6. Target high earners.
7. Fix spending dips.

### Results
- Built two fully interactive, visually clean Power BI dashboards.
- Improved understanding of data modeling, DAX, and Power BI storytelling.
- Learned how to create insight-driven visuals for business intelligence use cases

## Challenges & Solutions
Drill-through Implementation
Challenge: Drill-through was not initially working due to the missing Client_Num in the main visuals.
Solution: Integrated Client_Num into visuals to enable proper context transfer and filtering.
Learning: Improved understanding of Power BI filter context and interaction behavior.

## Dashboard Overview
![Dashboard Preview](https://github.com/data-by-kaka/credit-card-weekly-status-analysis/blob/main/Image/CreditCard.png)

![Dashboard Preview](https://github.com/data-by-kaka/credit-card-weekly-status-analysis/blob/main/Image/CreditCard%202.png)

### Contact
Feel free to connect or provide feedback!
