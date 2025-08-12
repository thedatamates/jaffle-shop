# Order Frequency vs Size Patterns Analysis

## Question
Our order frequency is down 8% but order size is up 12%. Are customers consolidating fewer, larger orders, or are we losing frequent purchasers to competitors?

## What We Have
- Historical order data with dates, values, and customer identifiers
- Customer ordering patterns and frequency metrics
- Product-level data showing order composition changes

## Approach
- Separate frequency decline from order size increase effects
- Compare behavior changes across customer cohorts
- Analyze product mix changes in larger vs smaller orders

## Deliverable
Behavioral shift analysis with assessment of revenue sustainability and customer engagement impact

**Final report should be written to: `reports/order-frequency-size-patterns/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/order-frequency-size-patterns/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `frequency-size-patterns-pivot.csv`
- Source data for pivot table: `frequency-size-source-data.csv`
- Customer behavior data: `customer-behavior.csv`
- Order metrics data: `order-metrics.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Customer cohorts or behavioral segments as rows
- Key performance metrics as columns including:
  - Order Frequency Change %
  - Average Order Size Change %
  - Revenue per Customer Impact
  - Customer Retention Rate
  - Purchase Pattern Shift Score
  - Revenue Sustainability Index
  - Competitive Risk Assessment
- Data sorted by revenue impact to assess business sustainability
- Clear numerical comparison enabling strategic response planning