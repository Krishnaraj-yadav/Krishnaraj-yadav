# VANTAGE360 Week 2 — Data Analyst Deliverables

Source: customers, transactions, products, customer_support, and marketing_campaigns datasets.

## Deliverables
- Automated data cleaning and validation pipeline
- Master analytical dataset at transaction grain
- Customer feature foundation at customer grain
- KPI dictionary and validation
- SQL query bank
- Return/discount analysis
- Campaign staging
- Revenue Command Center specification
- Executive insight brief

## Important governance notes
Governed revenue = SUM(final_amount) for valid Delivered transactions.

The source customers.csv fields total_orders, lifetime_value, and segment do not consistently reconcile with transaction-derived values. Governed analytical customer features therefore derive order/revenue metrics from valid Delivered transactions while preserving source fields separately.

The campaign source has no customer_id or transaction_id, so direct customer-to-campaign-to-transaction revenue attribution is not supported.

## Attrition proxy
High risk = >180 days since last delivered purchase; Medium = 91–180 days; Low = 0–90 days. This is an analytical inactivity proxy, not a supervised churn target.
