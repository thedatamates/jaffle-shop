# Customer Acquisition Cohort CLV Analysis

## Question
Which customer acquisition cohorts have the best 6-month CLV trajectory, and what does that tell us about our campaign timing?

## What We Have
- Customer first order dates for cohort definition
- Complete transaction history with order values and dates
- Customer lifetime spend and order counts

## Approach
- Group customers by acquisition month/quarter
- Track CLV growth curves over time for each cohort
- Compare cohort performance accounting for seasonal effects

## Deliverable
Cohort performance ranking with campaign timing recommendations

**Final report should be written to: `reports/cohort-clv-analysis/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/cohort-clv-analysis/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `cohort-clv-pivot.csv`
- Source data for pivot table: `cohort-clv-source-data.csv`
- Customer cohort data: `customer-cohorts.csv`
- CLV metrics data: `clv-metrics.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Acquisition cohorts (by month) as rows
- Key performance metrics as columns including:
  - 6-Month CLV per Customer
  - Cohort Size  
  - Total 6-Month CLV
  - 6-Month Retention Rate
  - Average Order Value
  - Performance vs Season Average (%)
  - CLV Rank
- Data sorted by CLV performance to identify top-performing acquisition periods
- Clear numerical comparison enabling campaign timing optimization decisions