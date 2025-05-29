# DATA ANALYST

I'm an entry-level Data Analyst passionate about transforming data into insights. This repo showcases projects focused on:

Data Cleaning & EDA (Python, Excel)

Visualization (Matplotlib, Seaborn, Tableau,Power BI)

SQL Analysis (PostgreSQL/MySQL/SQL server)

End-to-End Projects with real-world datasets

### Tools:

Python, SQL, Excel, Tableau, Power BI, Jupyter

### Education

Certified Data Analyst - Africa Agility

Bachelor of Business Management - Moi University

# Projects:

## Safe City – Hackathon Project

 Safe City is a civic-tech platform developed during a hackathon to empower citizens to report infrastructure and environmental issues in real-time. The goal was to bridge the gap between communities and decision-makers through technology, data, and local insight.

 Problem Statement:
How can we enable faster, data-driven responses to local infrastructure and environmental problems?

My Role:

Collected and cleaned mock citizen report data

Built pivot tables to analyze reports by time, location, and category

Designed interactive Excel dashboards with dynamic charts and filters

Used conditional formatting to highlight high-priority issues.

Tools Used:

Microsoft Excel (PivotTables, Charts, Conditional Formatting, Formulas)

# Health Records Dashboard – Power BI Project

This project analyzes and visualizes patient health data using Power BI. Built with a dataset sourced from Kaggle,the dashboard provides insights into hospital admissions, billing patterns, medical conditions, and patient demographics. It's a personal project aimed at strengthening skills in data visualization, storytelling, and healthcare analytics.

### Project Goals

Transform raw healthcare data into meaningful visuals  
Identify trends in admissions, conditions, and billing  
Explore relationships between demographics and medical outcomes  
Practice Power BI data modeling and dashboard design

### Dataset Overview

Source**: [Kaggle – Healthcare Dataset](#)  
**Columns include**:

| Category | Columns |
|---------|---------|
| Patient Info | `Name`, `Age`, `Gender`, `Blood Type` |
| Medical Details | `Medical Condition`, `Medication`, `Test Results` |
| Hospital Info | `Date of Admission`, `Discharge Date`, `Admission Type`, `Room Number`, `Doctor`, `Hospital` |
| Administrative | `Insurance Provider`, `Billing Amount` |

### Dashboard Features

- Admissions by age, gender, medical condition, and admission type.
- Billing analysis by insurance provider, doctor, and hospital
- Length of stay calculation (Discharge - Admission date)
- Medication usage and test result summaries
- Slicers for dynamic filtering across demographics and institutions

### Tools Used

- Power BI Desktop
- Power Query (Data transformation)
- DAX (Calculated columns/measures)
- Power BI visuals: bar charts, cards, filters, slicers, pie charts

  ### Insights
Blood Type Distribution: Evenly spread (~12.5% each type).

Admissions Flow: 55K total admissions; monthly fluctuations; average length of stay decreases over the year.

Billing Overview: UnitedHealthcare has the highest billing; total billing slightly over $0.1M.

Cost Effectiveness: Diabetes and Cancer are the most costly with longest stays; Asthma and Arthritis are more cost-effective.

Demographics: Average patient age is 51.54.

Test Results: Hypertension has the most abnormal results; Asthma shows more normal results; Obesity and Cancer have higher inconclusive rates.

###  Screenshots

<img width="676" alt="insights" src="https://github.com/user-attachments/assets/0b962b7f-0e67-4a28-8b96-1b98e1ddb5d4" />

# SALES ANALYSIS - PYTHON PROJECT.

This project performs an exploratory data analysis (EDA) on a supermarket sales dataset, focusing on customer behavior, sales trends, and performance across branches and product lines.

### Dataset Overview

The dataset contains sales records from a supermarket, including the following columns:

Invoice ID: Unique transaction identifier
- Branch: Store branch (A, B, or C)
- City: Location of the branch
- Customer type: Member or Normal
- Gender: Customer gender
- Product line: Category of the item sold
- Unit price: Price per unit of product
- Quantity: Number of units purchased
- Tax 5%: Tax applied to the purchase
- Total: Total amount (including tax)
- Date: Date of purchase
- Time: Time of purchase
- Payment: Payment method (Cash, Credit card, Ewallet)
- COGS: Cost of goods sold
- Gross margin percentage: Fixed at 4.7619%
- Gross income: Profit from the sale
- Rating: Customer satisfaction rating

  ### Objectives
- Identify sales trends by date and product line.
- Compare performance across branches.
- Analyze customer purchasing behavior by gender and type.
- Evaluate product line profitability and popularity.
- Discover insights from payment methods and gross income.
- Visualize key metrics using plots.

  ### Tools
- Python
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualization

  ### Sample Insights
- Most profitable branch and best-selling product line
- Peak sales days
- Preferred payment method by customer type
- Correlation between rating and gross income

  ### Sample codes

 #### To determine best selling product lines.
  
     df['Product line'].value_counts()

 #### Plotting a bar plot showing;

  #### Total sales by Gender.

     sns.barplot(x='Gender', y='Total', data=df)

  ##### Total sales by customer type

     sns.barplot(x='Customer type', y='Total', data=df)

 ### Time Series Trend
 
 #### Line graph 

     daily_sales = df.groupby('Date')['Total'].sum()
     daily_sales.plot(title="Daily Sales Trend")


 #### Screenshots

  <img width="896" alt="correlation" src="https://github.com/user-attachments/assets/316c07d0-c28b-4d01-9840-e5b6a47979a2" />

##### Insights gathered from the correlation.

Tax 5%, Total, cogs, and gross income are all perfectly positively correlated (1.00),this makes sense since they're mathematically linked.

Unit price shows a moderate positive correlation (~0.60) with revenue and income,higher priced items = more profit.

Quantity is not strongly correlated with total sales or income,Could mean higher quantity doesn’t always mean higher revenue (depends on price).

Rating has almost no correlation with any financial metrics.

     



     

 

  

  







 



