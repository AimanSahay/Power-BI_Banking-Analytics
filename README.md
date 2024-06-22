# Banking Analytics with Power BI

## Project Overview
Welcome to the Banking Analytics project repository! 
This project leverages Power BI to unlock financial insights from comprehensive banking datasets. The analysis is designed to guide strategic decisions in customer relationship management, risk assessment, and product offerings within the banking sector.

## Project Context
This project involved analyzing two comprehensive datasets: 'Banking Transactions' and 'Customer Account Details'. The objective was to create an interactive Power BI dashboard that not only visualizes transactional trends and customer profiles but also offers a holistic view of the banking ecosystem.

## Data Description
1. **Banking Transactions Dataset**: This dataset records detailed transaction data, including types, amounts, dates, branch information, and transaction times.
2. **Customer Account Details Dataset**: This dataset provides insights into account holders, covering account types, balances, interest rates, credit scores, loan amounts, and other account holder details.

## Work Done

1. **Data Importing and Initial Examination:** Both datasets were imported into Power BI. A preliminary examination was conducted to identify data quality issues and inconsistencies.
2. **Merging and Relating Datasets:** The datasets were merged using 'AccountNumber' as the key, ensuring accuracy and retention of all necessary information.
3. **Data Cleaning:** Missing data, duplicate entries, and irrelevant data points were addressed to ensure data quality. Data types were converted and normalized for consistency.
4. **Categorizing Transaction Types:** A new column was created to categorize transactions into broader categories based on 'TransactionType'.

## Key Analyses Performed

1. **Analysis of Account Balances:** Calculated the average account balance for each account type.<br>
2. **Currency Exchange Rate Impact:** Analyzed the impact of currency exchange rates on transaction amounts by converting all transactions to a standard currency.<br>
3. **Branch Activity Analysis:** Investigated which branch had the highest number of transactions.<br>
4. **Interest Rate and Balance Correlation:** Analyzed the correlation between interest rates and account balances using DAX.<br>
5. **Loan Amount and Credit Score Relation:** Examined the relationship between loan amounts and credit scores.<br>
6. **Transaction Trends Over Time:** Analyzed transaction trends to identify patterns or seasonal fluctuations.<br>
7. **Customer Loyalty Analysis:** Calculated the duration of each account's relationship with the bank.<br>
8. **High-Value Transaction Analysis:** Identified high-value transactions and analyzed their characteristics.<br>
9. **Analysis of Transaction Time Patterns:** Investigated patterns in transaction times.<br>
10. **Credit Score Distribution:** Analyzed the distribution of credit scores among account holders.<br>
11. **Correlation Between Account Age and Balance:** Explored the correlation between account age and balance.<br>
12. **Performance Rating of Branches:** Created a measure to rate branches based on transaction volume and value.<br>
13. **Extracting Key Information:** Extracted employment sector, years at current residence, and city of residence from the 'AccountHolderDetails' column.<br>
14. **Advanced DAX:** Risk Assessment Model: Developed a risk assessment model using transaction patterns, account balances, and credit scores.<br>
15. **Customer Demographics and Transaction Behavior:** Analyzed transaction behavior based on customer demographics.<br>
16. **Branch and Account Type Influence on Transactions:** Investigated the influence of branches and account types on transaction values and types.<br>
17. **Time Series Forecasting of Transactions:** Performed time series forecasting of transaction volumes.

## Dashboard Building
The project culminated in the creation of a comprehensive, interactive Power BI dashboard, segmented into four linked dashboards:

### Transactions and Balance Analysis
Analyzed transaction trends, identified high-value and rare transaction types, and conducted account balance analysis.

### Interest Rate, Credit Score, and Loan Analysis
Analyzed the distribution of credit scores, interest rates, and provided a drill-down of loan amounts by city and sector.

### Branch and Customer Analysis
Analyzed customer demographics, sector-wise transaction behavior, and branch performance.

### Insights Dashboard
Summarized key insights and findings from the analyses.

The dashboards incorporated slicers, filters, and page navigation to enhance interactivity and user experience.

## Conclusion
This project showcases the power of data analytics in the banking sector, providing deep insights into customer behavior, financial health, and operational efficiency. The interactive Power BI dashboard serves as a valuable tool for banking institutions to optimize services, enhance customer satisfaction, and manage financial risks effectively.

##### Feel free to explore the repository and the Power BI dashboard to gain a comprehensive understanding of the analysis and findings.
