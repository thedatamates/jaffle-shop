# Churn Warning Signs Analysis

## Question
Can you identify the 'warning signs' that predict when a good customer is about to churn? What behavioral changes occur 30-60 days before they stop ordering?

## What We Have
- Complete order history with dates and values
- Customer lifetime metrics and order patterns
- Product-level purchase data

## Approach
- Define "churned" vs "active" customers and focus on high-value segments
- Compare behavior 30-60 days before last order to active customers
- Identify statistically significant behavioral changes

## Deliverable
Churn prediction model with early warning indicators for retention campaigns

**Final report should be written to: `reports/churn-warning-signs/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/churn-warning-signs/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `churn-analysis-pivot.csv`
- Source data for pivot table: `churn-source-data.csv`
- Customer risk data: `customer-risk.csv`
- Behavioral metrics data: `behavioral-metrics.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Customer segments or risk groups as rows
- Key performance metrics as columns including:
  - Customer Count
  - Churn Rate
  - Days to Churn (Average)
  - Warning Sign Indicators
  - Revenue Impact
  - Prediction Accuracy
  - Recommended Actions
- Data sorted by risk level to identify highest priority segments
- Clear numerical comparison enabling proactive retention decisions