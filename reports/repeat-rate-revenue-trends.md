# Repeat Rate vs Revenue Trends Analysis

## Question
Our repeat rate is down, but revenue is up. Are we becoming more dependent on fewer high-value customers? What's the risk?

## What We Have
- Customer lifetime order counts and values
- Order timing data for repeat rate calculations
- Revenue distribution across customer segments

## Approach
- Track repeat rate and revenue growth trends over time
- Analyze revenue concentration (% from top customers)
- Model revenue impact scenarios if top customers churn

## Deliverable
Revenue growth decomposition and customer concentration risk assessment

**Final report should be written to: `reports/repeat-rate-revenue-trends/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/repeat-rate-revenue-trends/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `repeat-rate-trends-pivot.csv`
- Source data for pivot table: `repeat-rate-source-data.csv`
- Customer repeat metrics: `customer-repeat-metrics.csv`
- Revenue trend data: `revenue-trend-data.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Time periods as rows
- Key performance metrics as columns including:
  - Repeat Rate %
  - Revenue Growth %
  - Revenue from Top 20% Customers
  - Customer Concentration Index
  - Average Customer Value
  - Churn Risk Score
  - Revenue Sustainability Rating
- Data sorted by time period to track trend progression
- Clear numerical comparison enabling risk mitigation strategy development