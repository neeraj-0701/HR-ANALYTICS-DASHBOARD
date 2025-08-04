# 👩‍💼 HR Analytics Dashboard: Insights Across Workforce Dynamics
A dynamic and interactive Power BI dashboard offering deep insights into key HR metrics—spanning employee attrition, performance trends, diversity indicators, and workforce composition. Built to support data-driven HR decision-making.
## 📌 Short Description / Purpose
The HR Analytics Dashboard is a multi-page Power BI report designed to provide organizations with a comprehensive view of their workforce. From monitoring attrition patterns to analyzing employee performance and fostering diversity, this dashboard empowers HR teams to make informed strategic decisions.
## 🛠 Tech Stack
The dashboard was developed using the following tools and technologies:

📊 Power BI Desktop – Core platform for building the dashboard visuals and reports.

🧹 Power Query – Used for in-report transformation and shaping of smaller data tweaks.

🐼 pandas (Python) – Used for external data preprocessing and cleaning before import into Power BI.

🧠 DAX (Data Analysis Expressions) – Developed dynamic KPIs, calculated columns, and custom measures.

🔗 Data Modeling – Created relationships among key tables (Employee Data, Department, Attrition Details) to enable filterable, contextual analysis.

💾 File Format – .pbix (Power BI file) for editing and .png for dashboard previews.
## 📂 Data Source
Source: IBM HR Analytics Employee Attrition & Performance Dataset – Kaggle

Total Records: 1,470

Total Columns: 35

Data Includes:

Demographics: Age, Gender, Education

Employment Info: Job Role, Department, Monthly Income

Attrition Flags, Performance Ratings, Training Hours, Promotions, and more

This dataset provides a realistic simulation of workforce dynamics within a corporate setting, making it ideal for HR analytics projects, employee churn modeling, and performance analysis.

## 🌟 Features / Highlights
• Business Problem
HR teams often lack consolidated, interactive tools to analyze key metrics across attrition, performance, and diversity. Without a centralized dashboard, deriving actionable insights from raw data is time-consuming and inefficient.

• Goal of the Dashboard
To deliver a visual, multi-perspective dashboard that:

Tracks attrition trends and root causes

Evaluates employee performance by department and experience

Monitors diversity and inclusion across gender and job roles

Provides leadership with real-time HR metrics for strategic workforce planning

## Business Impact & Insights
📉 Attrition Reduction: Helps HR identify departments or job roles with high turnover and strategize retention efforts.

🎯 Performance Optimization: Identifies high-performing departments, links training hours with performance.

🌍 Diversity Goals: Supports D&I initiatives by visualizing gender gaps across roles and departments.

📈 Data-Driven HR: Provides leadership with a real-time pulse of the organization’s human capital, supporting evidence-based decisions.

##  Walkthrough of Key Visuals
### 📄 Page 1: HR Overview
KPIs: Total Employees, Attrition Rate, Avg Tenure

Visuals:

Donut Chart: Employee Count by Department

Donut Chart: Employee Count by Gender

Slicers: Department, Job Role, Gender

### 📉 Page 2: Attrition Analysis
KPIs:

Attrition Rate

Attrition Count

Avg Exit Age

Avg Tenure Exit


Visuals:

Clustered Column Chart: Attrition Count by Work Balance

Pie Chart: Top 5 Job Roles with Highest Attrition

Clustered Bar Chart: Attrition by Martial Status

Clustered Column Chart: Attrition Status Of Work Force

### 🚀 Page 3: Employee Performance
KPIs:

Avg Performance Score

Promotions Granted

Top Performers

% Promoted Employees

Visuals:

Line Chart: Performance Rating vs Training Times Last Year

Clustered Column Chart: Performance by Department

Area Chart: Performance By Working Years

Clustered Column Chart: Performance by Job Role


### 🌈 Page 4: Diversity and Inclusion
KPIs:

% Female Employees

Avg Male Income

Avg Female Income

Pay Gap Ratio

Visuals:

Stacked Column Chart: Gender Distribution by Job Role

Clustered Column Chart : Department vs Gender Count

Clustered Column Chart: Avg Monthly Income By Gender

Donut Chart: Employees By Gender Distribution 

## 📸 Dashboard Preview

### Page 1: HR Overview  
![HR Overview](SNAPSHOT%20OF%20DASHBOARD%20PAGE-1.png)

### Page 2: Attrition Analysis  
![Attrition Analysis](SNAPSHOT%20OF%20DASHBOARD%20PAGE-2.png)

### Page 3: Employee Performance  
![Employee Performance](SNAPSHOT%20OF%20DASHBOARD%20PAGE-3.png)

### Page 4: Diversity and Inclusion  
![Diversity and Inclusion](SNAPSHOT%20OF%20DASHBOARD%20PAGE-4.png)
