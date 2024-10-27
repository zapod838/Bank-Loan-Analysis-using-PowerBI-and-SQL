# Bank Loan Analysis Project

## Overview

This project focuses on analyzing bank loan data to provide insights into various key performance indicators (KPIs) related to loan applications, funding amounts, and repayment performance. Using **Power BI**, I created three interactive dashboards to visualize and analyze the data effectively. These dashboards aim to assist stakeholders in making data-driven decisions by providing detailed views of loan metrics, trends, and borrower profiles.

## Dataset

The dataset used in this project contains details about loan applications, funded amounts, borrower repayment history, and more. It enables analysis of trends over time and across different regions. The data file used is:

- **financial_loan.csv**: Contains data related to loan applications, funded amounts, borrower payments, and other attributes.

## Dashboards

### 1. Summary Dashboard

![Summary Dashboard](Power%20BI/Summary_Dashboard.png)

This dashboard provides a high-level overview of the loan metrics, focusing on the following KPIs:
- **Total Loan Applications**: Displays the total number of loan applications along with Month-to-Date (MTD) and Month-over-Month (MoM) metrics.
- **Total Funded Amount**: Highlights the total funds disbursed as loans, with MTD and MoM trends.
- **Total Amount Received**: Tracks the repayments received from borrowers, providing insights into the bank’s cash flow.
- **Average Interest Rate**: Shows the average interest rate applied to loans and its MoM variations.
- **Average Debt-to-Income Ratio (DTI)**: Indicates the financial health of borrowers by calculating the DTI.

### 2. Overview Dashboard

![Overview Dashboard](Power%20BI/Overview_Dashoard.png)

This dashboard offers a more detailed analysis of the loan data through various visualizations:
- **Monthly Trends by Issue Date** (Line Chart): Identifies seasonal and long-term trends in loan issuance.
- **Regional Analysis by State** (Filled Map): Highlights regional lending activities and disparities.
- **Loan Term Analysis** (Donut Chart): Breaks down the distribution of loans across different term lengths.
- **Employee Length Analysis** (Bar Chart): Analyzes the distribution of loans based on borrowers' employment length.
- **Loan Purpose Breakdown** (Bar Chart): Provides insights into the primary reasons for seeking loans.
- **Home Ownership Analysis** (Tree Map): Visualizes how home ownership affects loan applications and disbursements.

### 3. Details Dashboard

![Details Dashboard](Power%20BI/Details_Dashboard.png)

This comprehensive dashboard serves as a detailed report, providing a holistic view of the loan data. It includes:
- A consolidated view of loan-related metrics.
- Easy access to borrower profiles and loan performance details.
- An interactive interface for exploring key data points related to loan applications, funding, and repayments.


## How to Use

1. **Navigate to the Dataset Folder**: 
   Load the `financial_loan.csv` dataset into your analysis tool.
2. **Explore the Power BI Dashboards**:
   - Open the Power BI files or use the provided `.png` files for a quick overview.
   - Navigate through the dashboards to explore different insights.
3. **Run SQL Queries** (if applicable):
   - Use the provided SQL scripts in the `SQL` folder for additional data processing.

## Insights

This project helps in:
- Monitoring loan performance through key metrics like application trends, funded amounts, and repayment details.
- Understanding the distribution of loans based on regions, employment lengths, and homeownership status.
- Making data-driven decisions to improve the overall loan approval process and fund allocation strategies.

## Contributing

Contributions are welcome! If you find a bug or have suggestions for improvements, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
