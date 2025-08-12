# Location Performance Analysis

## Question
Our Chicago location is underperforming vs. projections. Is it location-specific factors (tax rate, local preferences) or are we cannibalizing our nearby stores?

## What We Have
- Transaction data by location with customer identifiers
- Location tax rates and opening dates
- Product sales mix by location

## Approach
- Compare key metrics across all locations
- Examine product mix differences by location
- Identify customer overlap between locations

## Deliverable
Root cause analysis for underperforming locations with improvement recommendations

**Final report should be written to: `reports/location-performance-analysis/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/location-performance-analysis/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `location-performance-pivot.csv`
- Source data for pivot table: `location-performance-source-data.csv`
- Location metrics data: `location-metrics.csv`
- Customer overlap data: `customer-overlap.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Store locations as rows
- Key performance metrics as columns including:
  - Revenue Performance vs Target
  - Customer Count
  - Average Order Value
  - Customer Overlap with Other Locations
  - Product Mix Performance
  - Tax Rate Impact
  - Cannibalization Index
- Data sorted by performance gap to prioritize improvement actions
- Clear numerical comparison enabling location-specific problem diagnosis