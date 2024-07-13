# Income Statement Dashboard

## Overview
This project showcases an Income Statement Dashboard built using Power BI. The dashboard provides a comprehensive view of a company's financial performance over two years, including key metrics such as Revenue, Cost of Sales (COS), Gross Profit, Operating Expense, and Net Profit. It also includes various visualizations to aid in financial analysis.

## Data
The data used in this project consists of the General Ledger (GL) entries of a company for two years (2022 and 2023). The data includes the following tables:
- **Data 2022**: General Ledger entries for the year 2022.
- **Data 2023**: General Ledger entries for the year 2023.
- **Date**: Date table to provide a comprehensive date dimension for time-based analysis.
- **Mapping Table**: A table used to map revenue and COS codes with the GL entries.
- **Layout**: A table used to organize the income statement in the correct order.

## Data Modeling
1. **Append GL Tables**: The GL 2022 and GL 2023 tables are appended to create a consolidated GL table.
2. **Date Table Join**: The consolidated GL table is joined with the Date table using the `DateKey` to enable time-based analysis.
3. **Mapping Table Join**: The consolidated GL table is joined with the Mapping Table using the `Account Code` to correctly categorize the GL entries.
4. **Income Statement Order**: The Layout table is used to arrange the income statement in the correct order for display in the dashboard.

## Measures
The following measures were created to facilitate the analysis and visualization of the financial data:
- **Total Revenue, Total COS, Total Expense, Gross Profit, Gross Margin, Net Profit, Net Profit Margin, Record, Current, Previous
**

## Dashboard Features
- **Key Metrics**: Displays key financial metrics such as Revenue, COS, Gross Profit, Net Profit, Gross Margin, and Net Margin.
- **Income Statement**: Provides a detailed income statement with current and previous year values.
- **PnL Breakdown**: Visualizes the Profit and Loss breakdown.
- **OPEX Breakdown**: Shows the breakdown of Operating Expenses.
- **Revenue vs COS vs GP**: Compares Revenue, COS, and Gross Profit over time.
- **Gross Profit vs Expenses vs Net Profit**: Compares Gross Profit, Expenses, and Net Profit over time.

## How to Use
1. Clone the repository to your local machine.
2. Open the Power BI file included in the repository.
3. Refresh the data to load the latest GL entries.
4. Explore the dashboard to analyze the company's financial performance.

## Screenshots
![image](https://github.com/user-attachments/assets/9fdca117-7043-40de-9ab2-54b954b3419e)


## License
This project is licensed under the MIT License.


## Contact
For any questions or feedback, please contact **Ashar Nadeem** at **asharnadeem2001@gmail.com**
