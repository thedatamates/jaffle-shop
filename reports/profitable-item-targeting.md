# Customer Targeting for Profitable Items

## Question
Our most profitable item has low sales volume. Can you identify which customer segments would be most likely to buy it with the right targeting?

## What We Have
- Product pricing and cost data for margin calculations
- Customer purchase history with product details
- Customer lifetime value and spending patterns

## Approach
- Identify high-margin, low-volume products
- Profile customers who currently buy these products
- Find similar customers who haven't purchased yet (lookalike modeling)

## Deliverable
Customer propensity model for high-margin items with targeted marketing recommendations

**Final report should be written to: `reports/profitable-item-targeting/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/profitable-item-targeting/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `profitable-targeting-pivot.csv`
- Source data for pivot table: `profitable-targeting-source-data.csv`
- Customer propensity data: `customer-propensity.csv`
- Product profitability data: `product-profitability.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Customer segments as rows
- Key performance metrics as columns including:
  - Propensity Score
  - Current Purchase Rate
  - Revenue Opportunity
  - Margin Impact Potential
  - Marketing Response Rate
  - Customer Count
  - ROI Projection
- Data sorted by revenue opportunity to prioritize targeting efforts
- Clear numerical comparison enabling profitable customer targeting strategy