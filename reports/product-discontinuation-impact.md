# Product Discontinuation Impact Analysis

## Question
We want to discontinue our 3 worst-performing products. What's the ripple effect - do customers who buy these also buy our high-margin items?

## What We Have
- Product performance metrics (sales volume, margin)
- Customer purchase history with product combinations
- Market basket data showing product relationships

## Approach
- Identify objectively worst-performing products
- Analyze cross-purchase patterns between poor and strong performers
- Model revenue impact of discontinuation including lost cross-sales

## Deliverable
Net profitability impact analysis with discontinuation recommendations

**Final report should be written to: `reports/product-discontinuation-impact/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/product-discontinuation-impact/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `discontinuation-impact-pivot.csv`
- Source data for pivot table: `discontinuation-source-data.csv`
- Product performance data: `product-performance.csv`
- Cross-sell analysis data: `cross-sell-analysis.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Products (worst performers) as rows
- Key performance metrics as columns including:
  - Direct Revenue Loss
  - Cross-sell Revenue Impact
  - Margin Improvement
  - Customer Churn Risk
  - Alternative Product Uptake
  - Net Profitability Change
  - Customer Segment Impact
- Data sorted by net profitability impact to guide discontinuation decisions
- Clear numerical comparison enabling informed product portfolio optimization