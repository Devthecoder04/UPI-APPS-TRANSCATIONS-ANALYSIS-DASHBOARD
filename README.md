UPI Transactions Analysis Dashboard | Power BI

An interactive Power BI Business Intelligence project focused on analysing UPI transaction performance, payment reliability and potential fraud indicators across multiple UPI applications.

The project explores different aspects of digital payment operations, including transaction volume, transaction value, success and failure rates, UPI app performance, customer activity, payment modes and suspected fraudulent transactions.

The objective is to transform raw UPI transaction data into meaningful insights that support business performance analysis, payment monitoring and risk investigation.

🎯 Project Objectives

Analyse transaction volume and transaction value trends.

Compare transaction performance across different UPI applications.

Identify payment failure patterns and possible reasons.

Monitor suspected fraudulent transactions and high-risk activity.

Evaluate app-wise performance to support business decisions.

📂 Dataset Overview

Dataset: UPI Transactions Dataset.

Source File: phonepay_raw_data.xlsx.

Dataset Type: Transaction-level dataset representing digital UPI payments.

Total Records: 502,887 transactions.

Total Columns: 22.

UPI Applications: 7.

Time Period: May 2026 (31 days).

The dataset covers:

Transaction details and amounts

UPI applications

Customer information

Payment status

Payment modes

Bank details

Merchant information

Transaction fees and cashback

Risk scores and suspected fraud indicators

Transaction dates and times

UPI Applications Analysed:

PhonePe

Google Pay

Paytm

Amazon Pay

BHIM

Cred Pay

WhatsApp Pay

🛠️ Tools & Technologies

Power BI Desktop – Data modelling, DAX and interactive report development.

Power Query – Data cleaning and transformation.

DAX – Measures, calculations and KPI development.

Excel – Source data management.

🔄 Data Cleaning & Transformation

Imported the Excel dataset into Power BI.

Reviewed column names, data types and table structures.

Handled missing values where appropriate.

Checked and removed duplicate records where necessary.

Corrected data types for numerical, categorical and date columns.

Prepared transaction data for analysis.

Verified important columns such as transaction ID, amount, status and risk score.

Prepared the data model for interactive reporting.

🏗️ Data Modelling

Organised the transaction data using the available tables, including:

Main Transaction Table

fact_table – Transaction details, amounts, status, risk scores, payment modes and merchant information.

Supporting Tables

app – UPI application-related information.

customer – Customer-related information.

Relationships were configured using matching key columns to support filtering and analysis across the report.

📊 Key DAX Measures

Total Transactions

Total Transaction Value

Successful Transactions

Failed Transactions

Success Rate %

Failure Rate %

Suspected Fraud Count

Suspected Fraud Rate %

High-Risk Transactions

Flagged Transaction Value

Transaction Share %

Advanced DAX functions used:

CALCULATE() · DISTINCTCOUNT() · DIVIDE() · SUM() · FILTER() · REMOVEFILTERS() · FORMAT()

📈 Power BI Report Pages

1. Transaction Overview

Overall transaction volume and transaction value.

Success and failure rate analysis.

Daily transaction trends.

Key performance indicators for UPI transactions.

2. UPI App Performance

Transaction volume comparison across seven UPI applications.

App-wise transaction value analysis.

Transaction share by UPI application.

Success and failure performance comparison.

3. Fraud Analysis

Suspected fraud transaction monitoring.

Fraud rate and high-risk transaction analysis.

Flagged transaction value analysis.

Key Influencers visual to explore factors associated with suspected fraud.

💡 Key Business Insights

KPI

Reported Result

Total Transaction Value

₹44.25 Cr

Success Rate

91%

Failed Transactions

7%

Suspected Fraud Rate

3.4%

Suspected Fraud Transactions

17,089

PhonePe Transaction Share

48.3%

Flagged Transaction Value

₹1.56 Cr

The overall transaction success rate was 91%, while approximately 7% of transactions failed, highlighting an opportunity to improve payment reliability.

PhonePe accounted for 48.3% of the total transaction share.

Approximately 3.4% of transactions were flagged as suspected fraud, requiring further investigation.

Risk score comparisons showed a higher average risk score for flagged transactions than for the overall transaction population.

Note: These figures represent the reported dashboard results. Suspected fraud indicators are not confirmed fraud cases.

🎛️ Power BI Features

Interactive charts and KPI cards.

UPI application performance comparison.

Dynamic DAX measures.

Transaction status analysis.

Fraud monitoring and risk analysis.

Key Influencers visual.

Interactive filtering and report exploration.

📁 Project Files

PowerBI/ – Interactive Power BI report (.pbix).

Presentation/ – Project presentation (.pptx).

Dataset/ – Source dataset (.xlsx).

👨‍💻 Author

Devaprakash

B.Tech Graduate in Artificial Intelligence and Data Science
Aspiring Data Analyst | Power BI | SQL | Python | Excel# UPI-APPS-TRANSCATIONS-ANALYSIS-DASHBOARD
