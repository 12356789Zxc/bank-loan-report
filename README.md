# Bank Loan Analysis Dashboard

## Project Description
This project presents a comprehensive bank loan analysis dashboard developed using SQL for data processing and Tableau for visualization. It provides in-depth insights into key lending metrics and loan portfolio performance through three interconnected dashboards: Summary, Overview, and Details. The dashboard enables data-driven decision-making for lending strategies, offers insights into loan portfolio health, and supports risk assessment through visualization of good vs bad loan metrics.

## Dashboard Screenshots

### Summary Dashboard
![Screenshot (20)](https://github.com/user-attachments/assets/660e94d3-8e30-47aa-9758-0b84cd5dcdb8)


### Overview Dashboard
![Screenshot (21)](https://github.com/user-attachments/assets/4efc93cb-9cb2-4ab0-a1e1-bf581ac3a4f2)


### Details Dashboard
![Screenshot (22)](https://github.com/user-attachments/assets/c00dfeaa-45d6-43f1-9457-f40495a8ffa8)


## Key Features

1. **Summary Dashboard**
   - Display of critical KPIs (total loan applications, funded amount, amount received, average interest rate, average DTI)
   - Visualization of good vs bad loan performance
   - Loan status grid showing detailed breakdowns by loan status

2. **Overview Dashboard**
   - Monthly application trends
   - State-wise analysis
   - Loan term distribution
   - Employee length analysis
   - Loan purpose analysis
   - Home ownership breakdown

3. **Details Dashboard**
   - Comprehensive data table view with key loan attributes
   - Filters for Purpose, Grade, and Verification Status
   - Flexible measure selection for analysis

## Technical Skills Demonstrated

- SQL for data extraction and processing
- Data visualization using Tableau
- Dashboard design and layout
- Interactive filtering and drill-down capabilities
- KPI definition and calculation
- Geospatial analysis
- Time series analysis

## Project Structure

- `data/`: Contains the bank loan data file (bank_loan_data.csv)
- `queries/`: Contains SQL query files for different parts of the analysis
- `docs/`: Contains documentation files, including field descriptions
- `tableau/`: Contains Tableau dashboard files and visualizations workbook and images
- `README.md`: Provides an overview of the project
- `.gitignore`: Specifies files and directories to be ignored by Git

## Instructions for Viewing/Using the Dashboard

1. **Tableau Public**: 
   - The dashboard is hosted on Tableau Public. You can view it here
     ((https://public.tableau.com/app/profile/malothu.bhanu.prakash/viz/BANKLOANSUMMARY/Summary?publish=yes)).
   - No installation is required to view the dashboard on Tableau Public.

2. **Local Viewing**:
   - Download the Tableau workbook file (.twbx) from this repository.
   - Install Tableau Reader (free) or Tableau Desktop (paid) from the [Tableau website](https://www.tableau.com/products/reader).
   - Open the downloaded .twbx file using Tableau Reader or Desktop.

3. **Navigation**:
   - Use the tabs at the bottom to switch between Summary, Overview, and Details dashboards.
   - Utilize filters on the left side to drill down into specific data subsets.
   - Hover over chart elements for tooltips with additional information.
   - Click on elements in some charts to filter other charts on the dashboard.

## Key Performance Indicators (KPIs) Analyzed

- Total Loan Applications (including MTD and PMTD)
- Total Funded Amount (including MTD and PMTD)
- Total Amount Received (including MTD and PMTD)
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)
- Good Loan vs Bad Loan Analysis
- Loan Status Overview

## Data Fields

For a complete description of the data fields used in this project, refer to the Field Descriptions document in the `docs/` directory. Key fields include Loan ID, Address State, Employee Length, Grade, Sub Grade, Home Ownership, Issue Date, Loan Status, Purpose, Term, Annual Income, DTI, Interest Rate, and Loan Amount.


## Contact

For any queries regarding this project, please open an issue in this repository.
