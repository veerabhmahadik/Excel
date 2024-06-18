
# Analyzing Bike Sales Trends, Patterns, and Insights & YumPizza Delivery Optimization

## Description
This repository contains two distinct projects: **Analyzing Bike Sales Trends, Patterns, and Insights** and **YumPizza Delivery Optimization**. Each project aims to analyze specific datasets to derive insights and optimize strategies for respective business needs.

### Analyzing Bike Sales Trends, Patterns, and Insights
This project explores and understands the demographic and financial characteristics of bike buyers. By analyzing a dataset of 1,026 entries, the project provides valuable insights into bike purchase behavior based on various demographic factors such as income, gender, and family structure. The analysis includes summary statistics, visualizations, and an interactive dashboard to help stakeholders make data-driven decisions.

### YumPizza Delivery Optimization
This project aims to optimize the delivery network of YumPizza, a chain of delivery-only pizzerias. The goal is to offer guaranteed delivery within 30 minutes to 49 neighborhoods while considering various constraints, including budget limitations. The project involves solving for the optimal pizzeria locations using Excel, performing sensitivity analysis, and suggesting changes in the supply chain strategy to maximize coverage within the budget.

## Technologies Used
- **Excel**: Used for data preprocessing, analysis, and solving optimization problems in both projects.
- **Python/R**: Used optionally for advanced data processing and analysis.

## Details About Use
### Analyzing Bike Sales Trends, Patterns, and Insights
#### Usage Examples
- **Summary Statistics Visualization**: Bar charts and box plots to represent the distribution of income, age, number of children, and number of cars among bike buyers.
- **Gender-Based Purchase Analysis**: Pie charts and bar charts to compare the proportion of bike purchases between male and female buyers.
- **Income and Purchase Correlation**: Scatter plots and line charts to show the relationship between income levels and bike purchase decisions.
- **Interactive Dashboard**: Allows users to filter data by various demographic factors to derive tailored insights.

#### Issues or Limitations
- The dataset may have missing or inconsistent data that could affect the accuracy of the analysis.
- The analysis is limited to the available demographic factors and does not account for other potential influencing factors.

#### Future Features
- Integration of additional data sources to provide a more comprehensive analysis.
- Advanced predictive modeling to forecast future bike sales trends.
- Enhanced interactivity in the dashboard with more filtering options and detailed drill-down capabilities.

### YumPizza Delivery Optimization
#### Part I: Without Budget Constraint
- Solved for the optimal pizzeria locations to cover all neighborhoods using Excel.
- Identified that 4 facilities (B, D, F, G) are needed to cover all neighborhoods at a total cost of $8,900.

#### Part II: With Budget Constraint
- Suggested changing the supply chain strategy to focus on maximizing the number of covered customers within a $6,000 budget.
- Solved for the optimal pizzeria locations using Excel under this strategy.
- Identified that 2 facilities (B, D) are needed to serve 41 neighborhoods at a total cost of $5,000.

#### Comparison and Observations
- The total cost dropped from $8,900 to $5,000, and the number of facilities decreased from 4 to 2.
- Emphasizes the importance of prioritizing coverage and considering budget constraints when making supply chain decisions.

## Dependencies
- **Excel**

### Instructions for Installation
3. **Excel**: Ensure you have Microsoft Excel installed (part of Microsoft Office Suite).

## How to Run the Projects
### Analyzing Bike Sales Trends, Patterns, and Insights
1. **Data Preparation**:
   - Open the `Bike Sales Data Analysis.xlsx` file in Excel and review the dataset.
   - Perform any necessary data cleaning and preprocessing.

2. **Visualization**:
   - Import the dataset into Power BI or Tableau.
   - Create the visualizations as described in the project details.

3. **Interactive Dashboard**:
   - Use Excel features to create pivot tables.
   - Apply filters and interactivity features to allow dynamic data exploration.

### YumPizza Delivery Optimization
1. **Data Preparation**:
   - Open the `YumPizza_Calculations.xlsx` file in Excel and review the dataset.
   - Perform any necessary data cleaning and preprocessing.

2. **Optimization**:
   - Use Excel Solver to solve for the optimal pizzeria locations under different constraints.
   - Perform sensitivity analysis as described in the project details.

## Folder Structure
- **Analyzing_Bike_Sales_Trends_Patterns_and_Insights**:
  - `Bike Sales Data Analysis Report.pdf`: Detailed report of the bike sales data analysis.
  - `Bike Sales Data Analysis.xlsx`: Dataset used for the analysis.
- **YumPizza**:
  - `YumPizza_Calculations.xlsx`: Excel file containing calculations and optimization results.
  - `YumPizza_ProblemStatement.docx`: Document outlining the problem statement and constraints.
  - `YumPizza_Report.pdf`: Detailed report of the delivery optimization analysis.
