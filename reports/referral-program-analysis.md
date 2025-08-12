# Referral Program Analysis

## Question
We launched a referral program 6 months ago. Can you identify customers who likely came through referrals and measure if they're more valuable long-term?

## What We Have
- Customer acquisition dates and order history
- Complete transaction data to measure CLV
- No direct referral tracking data

## Approach
- Look for unusual acquisition spikes that might indicate referral activity
- Compare customer cohorts from different time periods
- Measure CLV, retention, and behavioral patterns across cohorts

## Deliverable
Identification of likely referral customers with CLV comparison analysis

**Final report should be written to: `reports/referral-program-analysis/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/referral-program-analysis/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `referral-analysis-pivot.csv`
- Source data for pivot table: `referral-source-data.csv` 
- Customer acquisition data: `customer-acquisition.csv`
- CLV analysis data: `clv-analysis.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Customer acquisition periods as rows
- Key performance metrics as columns including:
  - Customer Count
  - Likely Referral %
  - Average CLV
  - Retention Rate
  - Acquisition Spike Indicator
  - Revenue per Acquisition
  - Program ROI Estimate
- Data sorted by CLV performance to assess referral program effectiveness
- Clear numerical comparison enabling referral program optimization