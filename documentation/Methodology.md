# Methodology

The development of this dashboard followed a structured, decision-oriented analytical approach designed to transform transactional data into clear and actionable business insights.

## Data Preparation & Modeling
Raw transactional and master data were cleaned, standardized, and structured to ensure consistency across key business entities such as products, customers, territories, and dates.

A **star schema data model** was implemented to support scalable analysis and reliable filtering across all dashboard pages.

## Business Logic & Core Metrics
Key business metrics were defined to reflect how performance is evaluated in a real-world retail environment.

Core measures such as **Revenue, Cost, Profit, and Margin** were established as the foundation for all analyses, ensuring consistency across executive and detailed views.

## Time Intelligence & Performance Comparison
A dedicated **calendar table** was created to enable time-based analysis and year-over-year comparisons.

This allowed revenue performance to be evaluated across different periods, supporting trend analysis and contextual performance assessment rather than isolated point-in-time reporting.

## Analytical Layers
The dashboard was designed using **layered analysis**, progressing from high-level performance to more granular insights:

- **Executive layer**: Overall revenue performance and trends  
- **Product layer**: Revenue concentration and Pareto (80/20) analysis to identify priority products  
- **Geographic layer**: Regional and city-level revenue distribution to assess market focus  
- **Customer layer**: Behavioral segmentation using Recency, Frequency, and Monetary (RFM) logic to support retention and prioritization decisions  

Each layer builds on the previous one, allowing users to move from overview to detail **without losing context**.

## Visualization & Insight Design
Visuals were selected and formatted to emphasize **clarity and decision-making** rather than visual complexity.

The layout prioritizes intuitive navigation, consistent metrics, and focused comparisons, ensuring stakeholders can quickly identify key drivers, patterns, and areas requiring attention.
