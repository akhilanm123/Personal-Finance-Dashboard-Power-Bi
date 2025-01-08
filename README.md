# Personal-Finance-Dashboard-Power-Bi
## Project Overview
The Finance Dashboard aims to provide a detailed visualization of income, expenses, and savings over time, enabling users to track financial performance and identify spending patterns. The goal is to help users assess whether they are saving and spending in proportion to their earnings.
## Dataset Used
- <a href="https://https://github.com/akhilanm123/Personal-Finance-Dashboard-Power-Bi/blob/main/Finance%20Database.xlsx">Personal Finanace Dataset</a>
## Technical Approach
##### Data Sources:
   Used Excel/CSV data files for financial records.
##### Data Transformation:
   Cleaned and transformed raw financial data using Power Query for better usability.
##### Visualization Tools:
- Line charts for trend analysis.
- Bar charts for category breakdowns.
- Card visuals for summary metrics.
##### DAX Measures: 
Created custom calculations for percentages (e.g., savings %, expense %) and aggregates (e.g., total income, net worth).

## Dashboard Interaction
-<a href="https://https://github.com/akhilanm123/Personal-Finance-Dashboard-Power-Bi/blob/main/Finance%20dashboard.pbix">Personal Finance Analysis</a>

## Key Features
#### 1. Summary Statistics:
- Total income and expenses over the years.
- Expense percentage (78% of income) and savings percentage (22% of income).
- Net worth generated (₹325.5K).
#### 2. Trend Analysis:
- Month-over-month (MoM) income changes, expenses, savings, and savings target trends from 2018 to 2021.
- Visualized using a line chart for easy interpretation of financial performance trends.
#### 3.Detailed Statement:
- Year-wise breakdown of income, expenses, and savings.
- Categories such as house rent, groceries, EMIs, health, leisure, and shopping under expenses.
- Savings allocated to mutual funds, emergency funds, fixed deposits, and liquid cash.
#### 4. Spending and Savings Distribution:
- Breakdown of expense categories with percentage contributions.
- Example: House rent accounts for 40.44% of expenses.
- Savings distribution highlighting investment in mutual funds (71.58%), emergency funds, and fixed deposits.
#### 5.Interactive Filters:
- Year and date filters to allow users to drill down into specific time periods.
- Dynamic visuals that update based on filter selection.
 ## Insights Derived
#### Expense Patterns: 
House rent, groceries, and EMIs are the predominant expenses, collectively constituting over 85% of total expenditures.
#### Savings Strategy: 
A significant portion of savings is directed towards mutual funds, indicating a preference for long-term investment.
#### Financial Trends: 
Post-2020 data shows an increase in savings, suggesting improved financial management or reduced spending.

## Tooltips Used:
#### Tooltip 1: Monthly Financial Trends: Income, Expenses, and Savings
![Monthly Financial Trends Income, Expenses, and Savings](https://github.com/user-attachments/assets/9e890649-ebb3-47b9-b0a6-6a2e3dbcf5a0)

This tooltip provides insights into financial performance over time, with three metrics being visualized:
###### 1. Total Income (Light Blue Bars):
Represents the total monthly income for the given period.
###### 2. Total Expense (Dark Blue Bars):
Indicates the total monthly expenditure.
###### 3. Savings % (Orange Line): 
Reflects the percentage of income saved each month, calculated as savings divided by income.

The tooltip helps identify trends, such as:

- Fluctuations in income and expenses.
- Changes in savings percentages, which may indicate improved financial management or varying income/expense patterns.
   #### Tooltip 2: Total Expenses
  ![Total Expenses](https://github.com/user-attachments/assets/6163ac65-685f-4a10-bc55-37e4bb45c6a3)


  This tooltip visualizes Total Expenses over time, broken down into key components:

##### Expense Categories:

###### 1. EMIs (Blue Line): 
Represents monthly expenditures on loans or installments.
###### 2. Groceries & Food (Light Blue Line): 
Covers daily essentials and food-related expenses.
###### 3. Health (Orange Line):
Tracks medical or healthcare spending.
###### 4. House Rent (Purple Line):
Indicates the rent paid monthly.
###### 5. Leisure (Pink Line): 
Includes expenses on entertainment and recreational activities.
###### 6. Shopping (Dark Purple Line): 
Tracks spending on shopping.
##### Trends and Insights:

- Each line highlights fluctuations in spending within its category over time.
- The tooltip aids in identifying spikes or reductions in specific expense types, helping users analyze patterns.
- This visualization offers a granular understanding of spending habits, empowering users to evaluate and manage their finances effectively.
     #### Tooltip 3: Total Savings
  ![Total Savings](https://github.com/user-attachments/assets/8190c4de-a41d-4249-81c8-623a8c5d4fff)

  This tooltip illustrates Total Savings over time, categorized into various saving components:

##### Savings Components:
###### Emergency Fund (Green Line):  
Represents funds set aside for unexpected financial needs.
###### Fixed Deposit (Dark Blue Line): 
Indicates savings invested in fixed deposits for stable returns.
###### Liquid Cash (Light Blue Line): 
Tracks readily available cash.
###### Mutual Funds (Pink Line): 
Reflects investments in mutual funds for potential growth.
##### Trends and Insights:

- Each line helps monitor the growth or reduction of specific savings types.
- Significant dips or rises highlight changes in financial strategy, such as increased investments or emergency fund withdrawals.
  #### Tooltip 4. Net Worth
  ![Net Worth](https://github.com/user-attachments/assets/47211216-4e61-49ef-80bc-d6d1025fae63)

  This chart visualizes the growth of net worth over time, showing data points at regular intervals (e.g., monthly). The trend line highlights steady financial progress, with net worth values increasing consistently. The tooltip appears when hovering over any point on the chart. It provides detailed insights into the financial data for that specific time period, including:

###### Date: The month and year of the data point.
###### Net Worth: The total net worth at that time.
###### Change from Previous Period: How much the net worth has increased or decreased compared to the prior period.
###### Percentage Growth (Optional): The rate of increase in net worth compared to the prior period.

## Final Conclusion:
In conclusion, the development of this interactive Finance Dashboard in Power BI has significantly enhanced the ability to monitor and analyze financial performance. By integrating dynamic visualizations and detailed tooltips, users can gain deeper insights into their income, expenses, and savings patterns. This project not only demonstrates proficiency in data analytics and visualization but also underscores the importance of effective financial data presentation for informed decision-making.






