# Bank Loan Report Project

## Overview

This project provides a detailed analysis of bank loan data using SQL and Tableau. The analysis covers various metrics including loan applications, funded amounts, received amounts, interest rates, debt-to-income ratios, and loan statuses. The primary objective is to gain insights into the performance and risk associated with different loan types and to support data-driven decision-making.

## Table of Contents

- [Project Structure](#project-structure)
- [Summary](#summary)
- [Key Performance Indicators (KPIs) Analyzed](#key-performance-indicators-kpis-analyzed)
- [Analysis Breakdown](#analysis-breakdown)
- [Getting Started](#getting-started)
- [Data Fields and Their Descriptions](#data-fields-and-their-descriptions)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Structure

- **data/**: Contains the bank loan data file (`bank_loan_data.csv`).
- **queries/**: Contains SQL query files for different parts of the analysis.
- **docs/**: Contains documentation files, including field descriptions and project description.
- **README.md**: Provides an overview of the project.
- **LICENSE**: Contains the license information for the project.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **tableau/**: Contains Tableau dashboard files and visualizations.

## Summary

This project aims to analyze and report on bank loan data to understand various metrics such as the number of loan applications, funded amounts, and the performance of loans. The analysis is performed using SQL for data extraction and processing, and Tableau for creating interactive dashboards that visualize the insights derived from the data.

## Key Performance Indicators (KPIs) Analyzed

- **Total Loan Applications**
- **Month-to-Date (MTD) Loan Applications**
- **Previous Month-to-Date (PMTD) Loan Applications**
- **Total Funded Amount**
- **MTD Total Funded Amount**
- **PMTD Total Funded Amount**
- **Total Amount Received**
- **MTD Total Amount Received**
- **PMTD Total Amount Received**
- **Average Interest Rate**
- **Average Debt-to-Income Ratio (DTI)**
- **Good Loan Issued (Fully Paid or Current)**
- **Bad Loan Issued (Charged Off)**
- **Loan Status Overview**

## Analysis Breakdown

1. **SQL Queries**: SQL is used to perform detailed data extraction and analysis. Queries are organized into separate files for summaries, overviews, and specific filters.
2. **Tableau Dashboards**: Interactive dashboards are created in Tableau to visualize the SQL query results, making it easier to interpret the data and gain actionable insights.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/12356789ZXC/bank-loan-report.git
    ```

2. Navigate to the project directory:
    ```bash
    cd bank-loan-report
    ```

3. Review the documentation in the `docs/` directory for detailed information about the project.

4. Execute the SQL queries in the `queries/` directory using your preferred SQL tool.

5. Open the Tableau files in the `tableau/` directory to view and interact with the dashboards.

## Data Fields and Their Descriptions

For a complete description of the data fields used in this project, refer to the [Field Descriptions](docs/field_descriptions.md) document.

### Example Data Fields

- **Loan ID**: Unique identifier for each loan.
- **Address State**: Indicates the borrower's location.
- **Employee Length**: Provides insights into the borrower's employment stability.
- **Employee Title**: Specifies the borrower's occupation or job title.
- **Grade**: Represents a risk classification assigned to the loan based on creditworthiness.
- **Sub Grade**: Refines the risk assessment within a grade.
- **Home Ownership**: Indicates the borrower's housing status.
- **Issue Date**: Marks the loan's origination date.
- **Last Credit Pull Date**: Records when the borrower's credit report was last accessed.
- **Last Payment Date**: Marks the most recent loan payment received.
- **Loan Status**: Indicates the current state of the loan.
- **Next Payment Date**: Estimates the date of the next loan payment.
- **Purpose**: Specifies the reason for the loan.
- **Term**: Defines the duration of the loan in months.
- **Verification Status**: Indicates whether the borrower's financial information has been verified.
- **Annual Income**: Reflects the borrower's total yearly earnings.
- **DTI (Debt-to-Income Ratio)**: Measures the borrower's debt burden relative to income.
- **Instalment**: Fixed monthly payment amount for loan repayment.
- **Interest Rate**: Represents the annual cost of borrowing expressed as a percentage.
- **Loan Amount**: Total borrowed sum.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
