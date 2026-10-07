# Banking Analytics Dashboard | Power BI

An interactive dashboard exploring customer activity and cash movement using synthetic banking data.

## Dashboard Preview

Dashboard screenshots will be added soon.

## Project Overview

This project analyzes 12,000 transactions across 1,000 customers and 1,200 accounts from January to June 2026. All financial amounts are in Saudi riyals (SAR).

## Tools Used

- Power BI Desktop
- Power Query (M)
- DAX
- Data Modeling

## Report Pages

### Overview
- Active customers and accounts
- Total transactions
- Total deposits and withdrawals
- Net cash movement
- Monthly transaction trends
- Active customers by city
- Filters by city, month, and account type

### Transactions
- Transaction-level details
- Gross transaction volume
- Average transaction amount
- Deposit share by transaction count
- Transaction-type filter

## Key Metrics

| Metric | Value |
|---|---:|
| Active Customers | 1,000 |
| Active Accounts | 1,200 |
| Transactions | 12,000 |
| Total Deposits | SAR 8,400,000 |
| Total Withdrawals | SAR 5,600,000 |
| Net Movement | SAR 2,800,000 |

These values represent the full dataset without filters.

Net movement equals deposits minus withdrawals. It does not represent bank profit or closing account balances.

## Data Model

Four related tables:
- Customers
- Accounts
- Transactions
- Calendar

One-to-many relationships connect customers to accounts, accounts to transactions, and calendar dates to transactions.

## How to Open

1. Download Banking-Analytics.pbix from this repository.
2. Open it in Power BI Desktop.
3. Explore the Overview and Transactions pages.
4. Use the filters to examine different customer groups and time periods.

## Data Source

All data is synthetic and used for learning and demonstration purposes. No real customer or bank data is included.

## Author

Asayl Saad
