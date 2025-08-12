# Location Order Value Drivers Analysis

## Question
Different locations have wildly different average order values. Is this driven by local demographics, product mix, or pricing strategy?

## What We Have
- Transaction data with location, products, and values
- Product pricing and category information
- Tax rates by location

## Approach
- Break down order value differences by components (product mix, quantity, pricing)
- Compare category preferences and their revenue impact by location
- Analyze how tax rates affect purchase decisions

## Deliverable
AOV driver analysis with location-specific optimization recommendations

**Final report should be written to: `reports/location-order-value-drivers/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/location-order-value-drivers/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `location-value-drivers-pivot.csv`
- Source data for pivot table: `location-drivers-source-data.csv`
- Location metrics data: `location-metrics.csv`
- Order value breakdown data: `order-value-breakdown.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Store locations as rows
- Key performance metrics as columns including:
  - Average Order Value
  - Product Mix Contribution
  - Price Point Distribution
  - Tax Rate Impact
  - Category Performance Index
  - Volume vs Value Trade-offs
  - Optimization Opportunity Score
- Data sorted by AOV potential to prioritize optimization efforts
- Clear numerical comparison enabling location-specific strategy development