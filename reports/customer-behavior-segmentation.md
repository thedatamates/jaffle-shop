# Customer Behavior Segmentation Analysis

## Question
Which customers are 'deal seekers' vs. 'convenience buyers' vs. 'product loyalists'? How do we message each differently?

## What We Have
- Purchase timing and promotional response patterns
- Product diversity in customer purchase history
- Price point preferences and order value distributions
- Repeat purchase behavior for specific products

## Approach
- Define behavioral indicators for deal-seeking, convenience, and loyalty behaviors
- Create scoring algorithms to classify customers into segments
- Develop messaging frameworks tailored to each segment's motivations

## Deliverable
Customer segmentation model with targeted messaging recommendations for each behavioral type

**Final report should be written to: `reports/customer-behavior-segmentation/<YYYY-mm-dd-hh-mm>.md` using current system time**

**Data Export Requirements:**
All analysis data should be exported as CSV files to: `reports/customer-behavior-segmentation/<YYYY-mm-dd-hh-mm>/`
- Main pivot table: `customer-segmentation-pivot.csv`
- Source data for pivot table: `segmentation-source-data.csv`
- Customer segment assignments: `customer-segments.csv`
- Behavioral metrics data: `behavioral-metrics.csv`
- Additional analysis tables as needed: `<descriptive-name>.csv`

## Desired Outcome
A comprehensive pivot table showing:
- Customer behavioral segments as rows (deal seekers, convenience buyers, product loyalists)
- Key performance metrics as columns including:
  - Segment Size
  - Average Order Value
  - Purchase Frequency
  - Price Sensitivity Score
  - Product Diversity Index
  - Lifetime Value
  - Preferred Communication Channel
- Data sorted by business value to prioritize segment targeting
- Clear numerical comparison enabling personalized marketing strategies