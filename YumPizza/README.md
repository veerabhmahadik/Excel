
# YumPizza Supply Chain Optimization Project

## Description

The YumPizza Supply Chain Optimization Project aims to optimize the location of pizzerias to ensure efficient delivery within a specified time constraint while minimizing costs. This project includes detailed problem statements, calculations, and reports on the optimal placement of pizzerias to cover all neighborhoods within a 30-minute delivery window. The analysis considers both unlimited budget and budget-constrained scenarios.

## Technologies

- **Data Format**: Excel (XLSX)
- **Reporting**: PDF, DOCX

## Details About Use

### Problem Statement

The `YumPizza_ProblemStatement.docx` outlines the objectives and constraints of the project. YumPizza aims to serve 49 neighborhoods with potential pizzeria locations identified based on their geographical coordinates and monthly leasing costs. A distance matrix is provided to measure delivery times between candidate locations and neighborhoods.

### Calculations

The `YumPizza_Calculations.xlsx` file contains all the necessary calculations for determining the optimal locations of pizzerias using Excel's Solver tool. The file includes distance matrices, demand data, leasing costs, and solver setups for both unconstrained and budget-constrained scenarios.

### Report

The `YumPizza_Report.pdf` provides a comprehensive analysis of the project, including:

1. **Initial Analysis (No Budget Constraint)**:
   - Optimal locations determined using Excel Solver.
   - Number of facilities needed: 4
   - Total monthly cost: $8,900
   - Full neighborhood coverage achieved.

2. **Budget-Constrained Analysis**:
   - Adjusted supply chain strategy considering a monthly budget of $6,000.
   - Optimal locations determined using the Maximal Covering Location Problem (MCLP) model.
   - Number of facilities needed: 2
   - Total monthly cost: $5,000
   - Number of neighborhoods served: 41
   - Total demand satisfied: 5,075

## Dependencies

- **Excel**: For calculations and using Solver for optimization.
- **Word Processor**: To view the problem statement (DOCX).
- **PDF Reader**: To view the comprehensive report (PDF).

## Usage Examples

### Solving for Optimal Locations in Excel

1. **Load Data**: Open `YumPizza_Calculations.xlsx` in Excel.
2. **Distance Matrix**: Review and update the distance matrix and leasing costs if necessary.
3. **Solver Setup**:
   - Go to the `Data` tab and click on `Solver`.
   - Set the objective to minimize total costs or maximize coverage, depending on the scenario.
   - Add constraints such as delivery time and budget limits.
   - Run Solver to find the optimal locations.
4. **Review Results**: Check the results for the selected pizzeria locations and their associated costs.

### Report Insights

1. **No Budget Constraint**:
   - All 49 neighborhoods are covered with a total monthly cost of $8,900.
   - Facilities B, D, F, and G are selected.

2. **Budget-Constrained Analysis**:
   - A budget of $6,000 limits the total number of facilities to 2.
   - Facilities B and D are selected.
   - 41 neighborhoods are covered, satisfying a total demand of 5,075.

### Issue or Limitations of the Project

- The analysis is based on the provided distance matrix and leasing costs, which may need updates for real-world applications.
- Budget constraints significantly impact the coverage and cost, requiring careful prioritization of neighborhoods.

### Future Features

- Integration with GIS software for more accurate geographical analysis.
- Dynamic adjustments to the distance matrix based on real-time traffic data.
- Advanced optimization models considering additional constraints like delivery capacity and variable demand.

## Instructions for Installation

1. **Excel**:
   - Ensure Microsoft Excel is installed on your computer.
   - Open `YumPizza_Calculations.xlsx` to view and manipulate the data.

2. **Word Processor**:
   - Use Microsoft Word or a compatible application to view `YumPizza_ProblemStatement.docx`.

3. **PDF Reader**:
   - Use Adobe Acrobat Reader or a similar application to view `YumPizza_Report.pdf`.

## Why Did You Choose Your Technology?

- **Excel**: Chosen for its powerful data analysis and optimization capabilities using Solver.
