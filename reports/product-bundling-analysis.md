# Product Bundling Analysis

## Question
We're considering bundling food + drink items. Which combinations do customers already buy together, and what's the price sensitivity?

## What We Have
- Order data with multiple items per transaction
- Product categorization (food vs drink)
- Individual product prices and costs

## Approach
- Market basket analysis to find frequently co-purchased items
- Compare order values of mixed vs single-category orders
- Identify customer segments most likely to buy bundles

## Deliverable
Top product combinations for bundling with pricing recommendations

**Final report should be written to: `reports/product-bundling-analysis/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/product-bundling-analysis/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `product-bundling-pivot.csv`
- Source data for pivot table: `product-bundling-source-data.csv`
- Product combination data: `product-combinations.csv`
- Market basket data: `market-basket.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Product combinations as rows
- Key performance metrics as columns including:
  - Co-purchase Frequency
  - Bundle Lift (vs individual purchases)
  - Average Bundle Value
  - Price Sensitivity Score
  - Customer Segment Affinity
  - Revenue Opportunity
  - Margin Impact
- Data sorted by revenue opportunity to prioritize bundle development
- Clear numerical comparison enabling optimal bundle strategy