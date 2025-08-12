# High-Value Customer Behavioral Patterns Analysis

## Question
We have 'high-value' customers but they all behave differently. Can you find the 3-4 distinct behavioral patterns within our top 20% revenue customers?

## What We Have
- Customer transaction history with detailed timing and values
- Product purchase preferences and category affinities
- Customer lifetime metrics and spending patterns

## Approach
- Define top 20% revenue customers objectively
- Use statistical clustering to identify distinct behavioral patterns
- Develop actionable customer personas for each cluster

## Deliverable
3-4 distinct high-value customer segments with targeted engagement strategies for each

**Final report should be written to: `reports/high-value-customer-patterns/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/high-value-customer-patterns/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `high-value-patterns-pivot.csv`
- Source data for pivot table: `high-value-source-data.csv`
- Customer cluster data: `customer-clusters.csv`
- Pattern metrics data: `pattern-metrics.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- High-value customer behavioral patterns as rows (3-4 distinct segments)
- Key performance metrics as columns including:
  - Segment Size
  - Average Lifetime Value
  - Purchase Frequency Pattern
  - Product Category Preferences
  - Order Timing Patterns
  - Engagement Response Rates
  - Revenue Contribution %
- Data sorted by revenue impact to prioritize engagement strategies
- Clear numerical comparison enabling targeted high-value customer management