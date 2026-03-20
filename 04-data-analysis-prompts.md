# 📊 Data Analysis Prompts (25 Prompts)

---

## Excel & Spreadsheets

### 1. Excel Formula Expert
```
I need an Excel formula to [TASK].

Data layout:
- Column A: [WHAT'S IN IT]
- Column B: [WHAT'S IN IT]
- [ADD MORE COLUMNS]

Data starts at row: [NUMBER]
Last row: [NUMBER OR "varies"]

Specific requirements:
- [CONDITION 1]
- [CONDITION 2]

Please provide:
1. The formula
2. Step-by-step explanation of how it works
3. Where to place it
4. How to drag/copy it
5. Alternative simpler approach if this is too complex
6. Error handling (what if cells are blank or wrong type?)
```

### 2. Pivot Table Designer
```
Help me design a pivot table for this data:

Data fields available: [LIST ALL COLUMNS]
Analysis goal: [WHAT INSIGHT DO YOU NEED]

Recommend:
1. Row fields
2. Column fields
3. Value fields (with aggregation: sum, count, average)
4. Filters
5. Calculated fields needed
6. Best chart type to visualize results
7. Step-by-step instructions to create in Excel/Google Sheets
```

### 3. Spreadsheet Automation
```
Automate this repetitive spreadsheet task:

[DESCRIBE WHAT YOU DO MANUALLY]

Frequency: [HOW OFTEN]
Tool: [EXCEL/GOOGLE SHEETS]

Provide:
1. VBA macro (Excel) or Apps Script (Google Sheets)
2. Step-by-step setup instructions
3. How to trigger it (button, schedule, on-edit)
4. Error handling
5. How to modify it when needs change
```

### 4. Data Cleaning Checklist
```
I have a messy dataset that needs cleaning:

Data source: [WHERE IT CAME FROM]
Rows: [APPROXIMATE NUMBER]
Columns: [LIST MAIN ONES]
Known issues: [DUPLICATES, MISSING VALUES, FORMATS, etc.]

Create a cleaning plan:
1. Duplicate detection and removal strategy
2. Missing value handling (per column)
3. Data type standardization
4. Outlier detection method
5. Format normalization (dates, currencies, etc.)
6. Validation rules
7. Formulas or scripts for each step
8. Quality check after cleaning
```

### 5. Dashboard Design
```
Design a dashboard for [PURPOSE].

Audience: [WHO WILL VIEW IT]
Data sources: [LIST]
Key metrics: [LIST 5-10 KPIs]
Update frequency: [REAL-TIME/DAILY/WEEKLY]

Provide:
1. Dashboard layout (wireframe description)
2. Chart type for each metric (with justification)
3. Filter/slicer recommendations
4. Color scheme and formatting rules
5. Conditional formatting rules
6. Drill-down hierarchy
7. Mobile view considerations
```

## SQL Queries

### 6. SQL Query Builder
```
Write a SQL query to [GOAL].

Database: [POSTGRESQL/MYSQL/SQLITE/etc.]
Tables:
- [TABLE1]: [COLUMNS]
- [TABLE2]: [COLUMNS]
- [ADD MORE]

Relationships: [HOW TABLES CONNECT]

Query needs to:
- [REQUIREMENT 1]
- [REQUIREMENT 2]
- [FILTERING CONDITIONS]
- [SORTING/GROUPING]
- [LIMIT/PAGINATION]

Provide:
1. The query with comments
2. Explain the approach
3. Index recommendations for performance
4. Alternative approach if data is large
5. How to handle NULL values
```

### 7. Complex Reporting Query
```
Build a reporting query for [REPORT NAME].

Report needs:
- Date range: [PERIOD]
- Grouping: [BY WHAT - daily/weekly/monthly, category, region]
- Metrics: [SUM, AVG, COUNT, custom calculations]
- Comparisons: [PERIOD OVER PERIOD, vs BUDGET, etc.]
- Top/Bottom: [RANKINGS]

Tables available:
[LIST TABLES AND KEY COLUMNS]

Provide:
1. Main query with CTEs for readability
2. Window functions for running totals/comparisons
3. CASE statements for categorization
4. Performance optimization tips
5. How to schedule this as a recurring report
```

### 8. Database Query Optimizer
```
Optimize this slow SQL query:

[PASTE QUERY]

Database: [TYPE AND VERSION]
Table sizes: [APPROXIMATE ROWS]
Current execution time: [SECONDS]
Indexes in place: [LIST EXISTING]

Analyze:
1. Explain plan interpretation
2. Identify bottlenecks
3. Rewrite for performance
4. Index recommendations
5. Partitioning suggestions if applicable
6. Caching strategy
7. Expected improvement
```

## Python Data Analysis

### 9. Pandas Data Analysis
```
Analyze this dataset using Python/Pandas:

Dataset description:
- Source: [FILE TYPE/URL]
- Columns: [LIST WITH TYPES]
- Rows: [APPROXIMATE]
- Goal: [WHAT INSIGHT DO YOU NEED]

Perform:
1. Data loading and initial inspection
2. Summary statistics
3. Missing value analysis
4. Distribution analysis (histograms, box plots)
5. Correlation analysis
6. Group-by analysis for [CATEGORIES]
7. Time series analysis (if dates present)
8. Anomaly detection
9. Key findings summary

Output as a Jupyter notebook with markdown explanations.
```

### 10. Data Visualization Generator
```
Create visualizations for this data:

[DESCRIBE DATA OR PASTE SAMPLE]

Library: [MATPLOTLIB/SEABORN/PLOTLY/ALTAIR]
Visualization needs:
1. [CHART TYPE] showing [WHAT]
2. [CHART TYPE] showing [WHAT]
3. [CHART TYPE] showing [WHAT]

Requirements:
- Professional styling (no default matplotlib look)
- Color-blind friendly palette
- Proper labels, titles, and legends
- Annotations for key data points
- Export-ready (300 DPI for presentations)
- Interactive where possible (Plotly)
```

### 11. Statistical Analysis
```
Perform statistical analysis on this data:

[DESCRIBE DATASET AND VARIABLES]

Research question: [WHAT ARE YOU TRYING TO PROVE/DISPROVE]
Hypothesis: [IF APPLICABLE]

Analysis to perform:
1. Descriptive statistics (mean, median, std, quartiles)
2. Normality test
3. Appropriate hypothesis test (t-test, chi-square, ANOVA, etc.)
4. Confidence intervals
5. Effect size calculation
6. Regression analysis (if applicable)
7. Interpretation in plain English
8. Limitations and caveats

Provide Python code using scipy/statsmodels with explanations.
```

### 12. Machine Learning Starter
```
Build a machine learning model for [PREDICTION TASK].

Dataset:
- Features: [LIST]
- Target variable: [WHAT TO PREDICT]
- Type: [CLASSIFICATION/REGRESSION]
- Size: [ROWS]

Provide complete pipeline:
1. Exploratory data analysis
2. Feature engineering suggestions
3. Train/test split strategy
4. Model selection (try 3+ algorithms)
5. Hyperparameter tuning
6. Cross-validation
7. Evaluation metrics and interpretation
8. Feature importance analysis
9. Model deployment considerations

Use scikit-learn with clear comments throughout.
```

## Business Analytics

### 13. KPI Definition Framework
```
Define KPIs for [BUSINESS/DEPARTMENT].

Business type: [WHAT YOU DO]
Department: [WHICH TEAM]
Goals: [STRATEGIC OBJECTIVES]
Current tracking: [WHAT YOU MEASURE NOW]

For each KPI provide:
1. Name and definition
2. Formula/calculation
3. Data source
4. Measurement frequency
5. Target/benchmark
6. Owner (who's responsible)
7. Visualization recommendation
8. Action triggers (what to do when KPI is off)

Organize by: Leading vs Lagging indicators.
```

### 14. Cohort Analysis
```
Design and implement a cohort analysis for [BUSINESS].

Business type: [E-COMMERCE/SAAS/APP]
Cohort definition: [SIGN-UP MONTH/FIRST PURCHASE/etc.]
Metric to track: [RETENTION/REVENUE/ENGAGEMENT]
Time period: [MONTHS OF DATA]

Provide:
1. SQL query to build cohort table
2. Python code to create cohort matrix
3. Heatmap visualization
4. Key insights to look for
5. Action items based on typical patterns
6. Comparison with industry benchmarks
```

### 15. A/B Test Analysis
```
Analyze this A/B test:

Test: [WHAT WAS TESTED]
Control: [DESCRIPTION]
Variant: [DESCRIPTION]
Duration: [HOW LONG]
Sample size: Control [N], Variant [N]
Primary metric: [WHAT]
Results: Control [VALUE], Variant [VALUE]

Analyze:
1. Statistical significance (p-value)
2. Confidence interval
3. Practical significance (effect size)
4. Power analysis (was sample size sufficient?)
5. Segment analysis (did it work differently for segments?)
6. Revenue impact projection
7. Recommendation: ship, iterate, or kill
8. Follow-up test suggestions
```

### 16. Funnel Analysis
```
Analyze this conversion funnel:

Steps:
1. [STEP NAME]: [NUMBER OF USERS]
2. [STEP NAME]: [NUMBER OF USERS]
3. [STEP NAME]: [NUMBER OF USERS]
[ADD MORE STEPS]

Business context: [WHAT TYPE OF FUNNEL]
Time period: [WHEN]

Provide:
1. Conversion rate at each step
2. Drop-off analysis (where and why people leave)
3. Benchmarking vs industry averages
4. Visualization (funnel chart)
5. Top 3 opportunities to improve
6. Estimated impact of 10% improvement at each step
7. Recommended A/B tests
```

### 17. Customer Segmentation
```
Perform customer segmentation on this data:

Data available:
- [LIST CUSTOMER DATA FIELDS]
Business type: [WHAT YOU SELL]
Goal: [MARKETING/PRODUCT/PRICING]

Approach:
1. RFM analysis (Recency, Frequency, Monetary)
2. K-means clustering
3. Segment profiles (who is in each segment)
4. Size and value of each segment
5. Recommended strategy per segment
6. Visualization of segments
7. SQL to tag customers with segment labels
```

## Data Engineering

### 18. ETL Pipeline Design
```
Design an ETL pipeline for [USE CASE].

Sources: [LIST DATA SOURCES]
Destination: [DATA WAREHOUSE TYPE]
Volume: [DATA SIZE]
Frequency: [REAL-TIME/BATCH]
SLA: [FRESHNESS REQUIREMENT]

Provide:
1. Architecture diagram (describe)
2. Extract logic per source
3. Transform rules and business logic
4. Load strategy (incremental vs full)
5. Error handling and retry logic
6. Data quality checks
7. Monitoring dashboard
8. Code in [PYTHON/SQL/SPARK]
```

### 19. Data Model Designer
```
Design a data model for [ANALYTICS USE CASE].

Business domain: [INDUSTRY]
Key business processes: [LIST]
Reporting needs: [WHAT REPORTS]

Design:
1. Dimensional model (star/snowflake schema)
2. Fact tables (with grain definition)
3. Dimension tables (with SCD type)
4. Bridge tables (for many-to-many)
5. DDL scripts
6. Sample data for testing
7. Common query patterns
```

### 20. Data Quality Framework
```
Create a data quality framework for [SYSTEM].

Critical data elements: [LIST]
Data consumers: [WHO USES THIS DATA]
Current pain points: [KNOWN ISSUES]

Framework:
1. Quality dimensions (accuracy, completeness, timeliness, consistency)
2. Validation rules per field
3. Automated checks (SQL assertions)
4. Alerting thresholds
5. Data quality dashboard
6. Remediation procedures
7. SLA definitions
8. Root cause analysis template
```

## Reporting & Presentation

### 21. Executive Report Generator
```
Create an executive report from this data:

[PASTE DATA OR DESCRIBE]

Audience: [C-LEVEL/BOARD/DEPARTMENT]
Report period: [TIMEFRAME]
Previous period: [FOR COMPARISON]

Structure:
1. Executive summary (3 key takeaways)
2. Performance overview (vs targets and prior period)
3. Deep dive on [KEY AREA]
4. Risk/opportunity analysis
5. Recommendations (prioritized)
6. Appendix with detailed data

Format each section with clear headers, use data tables where appropriate, and highlight variances with red/green.
```

### 22. Financial Analysis
```
Perform financial analysis on this data:

Revenue: [NUMBERS BY PERIOD]
Costs: [BREAKDOWN]
Industry: [SECTOR]
Comparison: [YOY/SEQUENTIAL/BUDGET]

Analyze:
1. Revenue growth rate and trends
2. Gross margin analysis
3. Operating expense ratio
4. Unit economics (if applicable)
5. Cash flow implications
6. Break-even analysis
7. Forecasting (next 12 months)
8. Sensitivity analysis (best/worst/base case)
9. Peer comparison
10. Recommendations
```

### 23. Survey Analysis
```
Analyze survey results:

Survey topic: [WHAT]
Respondents: [NUMBER AND WHO]
Questions: [LIST WITH RESPONSE TYPES]

Analysis:
1. Response rate and completion analysis
2. Descriptive statistics per question
3. Cross-tabulation between key questions
4. NPS/CSAT score calculation (if applicable)
5. Open-ended response themes (sentiment analysis)
6. Demographic breakdowns
7. Statistically significant differences between groups
8. Key insights and recommendations
9. Visualizations for each finding
```

### 24. Competitor Analysis Data
```
Create a data-driven competitor analysis for [YOUR COMPANY] vs [COMPETITORS].

Industry: [SECTOR]
Data available: [LIST - pricing, features, reviews, market share, etc.]

Analyze:
1. Feature comparison matrix
2. Pricing analysis
3. Market positioning map (2x2 matrix)
4. Strengths and weaknesses per competitor
5. Customer sentiment comparison (from reviews)
6. Growth trajectory
7. Market share trends
8. Opportunities and threats
9. Recommendation: where to compete and where to differentiate
```

### 25. Forecasting Model
```
Build a forecasting model for [METRIC].

Historical data: [DESCRIBE - how much history, granularity]
Metric: [WHAT TO FORECAST]
Forecast horizon: [HOW FAR AHEAD]
Seasonality: [YES/NO, WHAT PATTERN]
External factors: [LIST ANY]

Provide:
1. Data preparation and exploration
2. Multiple models (moving average, exponential smoothing, ARIMA, Prophet)
3. Model comparison (MAE, RMSE, MAPE)
4. Best model selection with justification
5. Forecast with confidence intervals
6. Visualization (historical + forecast)
7. Model maintenance plan (when to retrain)
8. Python code for the complete pipeline
```
