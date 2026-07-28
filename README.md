# Dummy-Linear-Regression-Analysis
Project Scope: Target Revenue Analysis

Client: Chapman Wealth Management Engagement Team: QuantFolio Solutions Prepared for: Hypatia (Manager) Data Source: qSales_2024.csv (Target Corporation quarterly revenue)

1. Objective

Chapman Wealth Management is evaluating a potential investment in Target Corporation. This engagement will use quarterly revenue data to build a regression model that explains historical revenue patterns and surfaces insights relevant to the investment decision.

2. Scope of Work
2.1 Data Exploration
Load qSales_2024.csv and inspect structure, date range, and data quality (missing values, outliers).
Visualize quarterly revenue over time to identify recurring patterns (e.g., seasonality, trend, cyclical spikes tied to specific quarters such as holiday-quarter effects).
2.2 Model Development
Define exactly 2 dummy variables based on patterns observed in exploration (e.g., specific quarters that consistently over/under-perform, such as Q4 holiday effect or a post-pandemic structural shift — to be confirmed once data is examined, not assumed in advance).
Build a multiple regression model: Revenue = β0 + β1(Time) + β2(Dummy1) + β3(Dummy2) + ε
Report coefficients, statistical significance (p-values), R², and adjusted R².
2.3 Analysis Output
Produce a chart overlaying actual revenue against model-predicted revenue.
Draft a brief memo to Chapman Wealth Management covering:
What each dummy variable represents in business terms
Model fit and explanatory power (R², significance of coefficients)
Key takeaways relevant to the investment decision (e.g., predictability of revenue, seasonality risk, growth trend)
3. Deliverable
A single Google Colab notebook containing: data loading, exploration visuals, model code, results, prediction visualization, and the written memo.
Sharing enabled ("Anyone with the link can view" or as required by submission instructions).
4. Out of Scope
Forecasting beyond the historical data window (unless separately requested).
Comparison against other retailers or benchmark indices.
Valuation or price-target recommendations — this analysis is limited to revenue pattern interpretation, not investment recommendations.
5. Assumptions & Open Items
The specific dummy variables cannot be finalized until the actual data patterns in qSales_2024.csv are examined — I do not have a verified source for what those patterns are yet, since the file hasn't been reviewed.
"Time" as an independent variable is assumed to be a sequential period index (e.g., 1, 2, 3...) unless the dataset specifies otherwise.
Submission format (Colab-specific) means final deliverable steps (enabling sharing, checking view permissions) need to be done manually in Google Colab — that's not something I can do on your behalf.
