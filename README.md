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

## Approach
- Cleaned and transformed customer and transaction datasets
- Built a data model using relationships based on Client_Num
- Created calculated fields and measures using DAX

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

## Key Insights
- Customer distribution varies across income and age groups, highlighting distinct financial segments.
- Spending behavior is concentrated in bills, fuel, and entertainment, indicating major revenue drivers.
- Revenue shows fluctuations week-over-week due to missing weeks in the dataset.
- Higher-income customers generally have higher credit limits.
- Customer satisfaction scores provide insight into user experience across segments.

## Challenges & Solutions
Drill-through Implementation
Challenge: Drill-through was not initially working due to the missing Client_Num in the main visuals.
Solution: Integrated Client_Num into visuals to enable proper context transfer and filtering.
Learning: Improved understanding of Power BI filter context and interaction behavior.

## Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling & Visualization

## Dashboard Overview
![Dashboard Preview](https://github.com/amieecode/credit-card-weekly-status-analysis/blob/main/Image/credit%20card.png)

![Dashboard Preview](https://github.com/amieecode/credit-card-weekly-status-analysis/blob/main/Image/credit%20card%202.png)

### Contact
Feel free to connect or provide feedback!
