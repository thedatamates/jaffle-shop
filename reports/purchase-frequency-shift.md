# Purchase Frequency Shift Analysis

## Question
We're seeing 15% more customers make only 1-2 purchases this year. Is this a seasonal shift, product mix issue, or are we attracting one-time buyers?

## What We Have
- Customer lifetime order counts
- Order timing and frequency patterns
- Customer acquisition dates for cohort comparison
- Product purchase patterns by customer segment

## Approach
- Compare purchase frequency distribution across acquisition cohorts
- Analyze time between first and second purchase trends
- Examine product mix differences between frequency segments

## Deliverable
Root cause analysis of purchase frequency decline with recommendations

**Final report should be written to: `reports/purchase-frequency-shift/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/purchase-frequency-shift/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `frequency-shift-pivot.csv`
- Source data for pivot table: `frequency-shift-source-data.csv`
- Customer frequency data: `customer-frequency.csv`
- Cohort analysis data: `cohort-analysis.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Customer acquisition cohorts as rows
- Key performance metrics as columns including:
  - 1-2 Purchase Customer %
  - Average Purchase Frequency
  - Time to Second Purchase
  - Product Mix Preference
  - Cohort Size
  - Revenue Impact
  - Seasonal Adjustment Factor
- Data sorted by frequency decline impact to identify root causes
- Clear numerical comparison enabling targeted retention strategy development