# Banking-Dashboard
This project is an attempt to develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
With our dashboards which are created using Power BI, it helps the company make decisions based on the applicant’s profile whether the applicant is likely to repay the loan, thereafter approving the loan otherwise not.

# Dataset
The dataset contains information about the bank loans, bank deposits, Business Lendings and others, as well as client details like Name, Gender, Occupation.
There is another table which specifies the names of Investment Advisors that is linked to the main dataset through primary key and foreign key.
The dataset is sourced from MySQL Database

# Tech Usage
Power BI Desktop – Data modeling & interactive visualizations 
DAX (Data Analysis Expressions) – Custom measures & calculated columns 
Power Query (M Language) – Data transformation and preprocessing 
SQL – Source data in SQL tables, later imported to PowerBI Desktop
Jupyter Notebook - Exploratory Data Analysis with Python

# Data Cleaning
- Creating a new column "Engagement Timeframe" in client-banking column which tells about the time line of the clients in banks
- Creating a new column Engagment Days in Client-Banking table how many days the client spent from the date of joining in banks
- Creating bins for the Estimated Income < 100000 as low and <300000 as Mid with the column named as Income Band in Clients-Banking table.
- Creating a new column named as Processing Fees for the column Fee Structure. If fee structure is "high" then processing fee would be 0.05

# Highlights
- There are certain KPIs listed below which helps the business gather information of the total loan amount and all other things of a particular investor.
- Total Clients:  Total number of clients in the bank.
- Total Loan: Bank Loan + Business Lending + Credit Cards Balance
- Bank Loan: The loan amount to be repaid by the client to bank.
- Business Lending: The loan amount given to small business.
- Total Deposit: The amount deposited by particular investors in bank
- Total Fees: The amount charged by the bank for account set-up , maintenance charges etc.
- Bank Deposit: The money put in the bank.
- Checking Account Amount: An account where you have easy access to your money for daily transactional needs.
- Total CC Amount: A short-term source of financing for a company by a bank.
- Saving Account Amount: An interest-bearing deposit account held at a bank.
- Foreign Currency Amount: An amount held in an account held in a currency that is not the currency of India
- Credit Cards Balance: Total amount of money currently owned by a cardholder to their credit card bank.
