# DA-13 Executive Retention Story

## What is happening
- 4,769 of 4,999 customers are repeat customers (95.4%).
- 1,452 customers (29.0%) meet the Week 2 high attrition-risk proxy based on recency.
- Average historical LTV is ₹11,787.92.

## Valuable customers
- The high-value group is defined as the top 25% by historical lifetime revenue.
- 227 customers are both high-value and high-risk under the analytical proxy.

## ML risk signal
- The supplied ML file scores 4,961 customers.
- ML categories: Medium 2,122; Low 1,938; High 901.
- Exact category agreement with the analytical proxy is 57.1%.

## Interpretation
These are evidence-based prioritization signals. The analytical proxy is recency-based and the ML file contains risk scores/categories. The supplied ML CSV does not include time-based test metrics, model version details, features, or threshold documentation, so model quality beyond the provided scores is not assessed here.