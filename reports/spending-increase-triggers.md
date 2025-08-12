# Spending Increase Triggers Analysis

## Question
We're seeing weird patterns where some customers suddenly increase spending 3x. Can you reverse-engineer what triggers this behavior change?

## What We Have
- Customer lifetime spending patterns and order history
- Product purchase data and order composition
- Timing data for all customer transactions

## Approach
- Identify customers with dramatic spending increases (3x+ jumps)
- Analyze what happened in the months leading up to the increase
- Look for common patterns in product mix, timing, or order behavior

## Deliverable
Analysis of spending increase triggers with recommendations for replicating the behavior in other customers

**Final report should be written to: `reports/spending-increase-triggers/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/spending-increase-triggers/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `spending-triggers-pivot.csv`
- Source data for pivot table: `spending-triggers-source-data.csv`
- Customer spending patterns: `customer-spending-patterns.csv`
- Trigger event data: `trigger-events.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Trigger events or patterns as rows
- Key performance metrics as columns including:
  - Customer Count Affected
  - Average Spending Increase %
  - Trigger Frequency
  - Time to Spending Change
  - Revenue Impact
  - Replication Feasibility Score
  - Implementation Cost
- Data sorted by revenue impact to prioritize trigger replication efforts
- Clear numerical comparison enabling systematic spending increase strategy