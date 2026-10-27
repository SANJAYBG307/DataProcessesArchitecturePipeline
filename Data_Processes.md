━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 
1. DATA SOURCES & DATA COLLECTION 
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 
 
PURPOSE: 
Identify where the required business data exists. 
 
1. FILE-BASED DATA 
   • CSV 
   • Excel 
   • JSON 
   • Parquet 
   • XML Files 
 
2. RDBMS 
   • MySQL 
   • PostgreSQL 
   • SQL Server 
   • SQLite 
   • Oracle 
 
3. NoSQL DBMS 
   • MongoDB 
   • Cassandra 
   • Redis 
 
4. CLOUD STORAGE / DATA LAKES 
   • Amazon S3 
   • Azure Data Lake Storage 
   • Google Cloud Storage 
 
5. CLOUD DATA WAREHOUSES 
   • Snowflake 
   • Amazon Redshift 
   • Google BigQuery 
   • Azure Synapse 
 
6. APIs 
   • REST APIs 
   • SOAP APIs


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
2. DATA PROFILING
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
PURPOSE: 
Understand baseline data structure and issues before any cleaning or analysis.

1. Row Count Analysis
2. Column / Schema Analysis
3. Data Type Analysis
4. NULL Analysis
5. Duplicate Analysis
6. Distinct / Cardinality Analysis
7. Min / Max Analysis
8. Average / Median Analysis
9. Pattern / Format Analysis


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
3. DATA QUALITY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
PURPOSE: 
Determine whether the data is trustworthy and usable. 

1. Completeness
2. Validity
3. Consistency
4. Uniqueness
5. Timeliness / Freshness
6. Data Type Validity
7. Referential Integrity

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
4. DATA CLEANING
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PURPOSE: 
Fix the data-quality problems identified during profiling and quality checks.

1. Remove Duplicates
2. Handle Missing / NULL Values
3. Correct Data Types
4. Standardize Text Values
5. Trim Whitespace
6. Standardize Date / Time
7. Handle Invalid Values
8. Remove Unwanted Columns
9. Rename Columns
10. Remove Special / Unwanted Characters
11. Standardize Case


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
5. DATA TRANSFORMATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
PURPOSE: 
Convert cleaned data into the required downstream structure and form.

1. Select Columns
2. Filter Rows
3. Create Derived Columns
4. Group By
5. Aggregation
6. Join
7. Pivot
8. Unpivot
9. Window Functions


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
6. DATA PREPARATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PURPOSE: 
Make transformed data ready for analytics and basic ML workflows.

1. Data Selection
2. Data Type Conversion
3. Feature Creation
4. Feature Selection
5. Categorical Encoding
6. Numerical Scaling
7. Outlier Treatment
8. Schema Alignment
9. Train / Validation / Test Split
10. Data Leakage Prevention
11. Data Versioning


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
7. EDA — EXPLORATORY DATA ANALYSIS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PURPOSE: 
Explore the prepared data to understand patterns, distributions, 
relationships and anomalies.

1. Dataset Overview
2. Row & Column Analysis
3. Data Type Analysis
4. Missing Value Analysis
5. Duplicate Analysis
6. Distribution Analysis
7. Univariate Analysis
8. Bivariate Analysis
9. Outlier Analysis
10. Group / Segment Analysis
11. Relationship Analysis
12. Time-Series Analysis
13. Trend Analysis
14. Seasonality Analysis
15. Anomaly Analysis


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
8. DATA ANALYSIS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
PURPOSE: 
Answer business questions and explain what happened, why it happened, 
and what it means.

1. Descriptive Analysis
2. KPI Analysis
3. Trend Analysis
4. Comparative Analysis
5. Contribution Analysis
6. Variance Analysis
7. Root Cause Analysis
8. Anomaly Analysis


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
9. DATA MINING
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PURPOSE: 
Discover hidden patterns, relationships, groups, anomalies and 
predictive signals that are not obvious through ordinary analysis.

1. Classification
2. Clustering
3. Regression
4. Anomaly / Outlier Detection


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
10. INSIGHT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
1. Convert findings into clear business insights
2. Quantify expected impact
3. Prioritize insights by business value

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
11. RECOMMENDATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
1. Map each insight to one recommendation
2. Add expected impact and effort
3. Define success metric for each recommendation

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
12. BUSINESS DECISION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
1. Compare options using impact vs effort
2. Select approach with decision rationale
3. Assign owner and decision timeline

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
13. ACTION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
1. Create action plan with tasks and deadlines
2. Track execution through KPIs and reporting
3. Run post-implementation validation and feedback loop

