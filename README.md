## Databricks - A high level summary of my day-wise learnings
### Day 1 – Databricks Basics

- Understood what Databricks is and why it is used over Pandas and Hadoop for large-scale data processing
- Learned the high-level idea of the Lakehouse architecture
- Explored Databricks Workspace, Compute, and data browsing concepts
- Created the first Databricks notebook
- Ran basic PySpark commands

### Day 2 – Apache Spark Fundamentals

- Learned Spark’s high-level architecture (Driver, Executors, DAG)
- Understood the difference between Spark DataFrames and RDDs
- Learned why Spark uses lazy evaluation and when execution is triggered
- Used Databricks notebook magic commands (`%python`, `%sql`, `%fs`)
- Ran operations using filter, select, groupBy, orderBy

### Day 3 – PySpark Data Operations

- Compared PySpark and Pandas for large-scale data processing
- Performed joins (inner, left, right, outer) on Spark DataFrames
- Used window functions for running totals and rankings
- Understood window functions vs groupBy aggregations
- Learned when and why to use (or avoid) User-Defined Functions (UDFs)

### Day 4 – Delta Lake Fundamentals

- Learned what Delta Lake is and how it adds reliability on top of Parquet
- Understood ACID transactions and their role in safe concurrent reads/writes
- Clearly distinguished ACID Consistency from Schema Enforcement
- Learned how schema enforcement prevents invalid data from entering tables
- Created Delta tables using managed approach
- Observed with examples how schema enforcement works

### Day 5 – Delta Lake Advanced Operations

- Learned Delta Lake time travel and table version history
- Understood MERGE operations for safe upserts
- Learned how OPTIMIZE reduces small files and improves read performance
- Understood ZORDER for clustering data after OPTIMIZE to speed up queries
- Learned how VACUUM cleans up old data and affects time travel

### Day 6 – Medallion Architecture & Incremental Processing

- Learned the Bronze → Silver → Gold (Medallion) architecture and responsibilities of each layer
- Understood best practices for raw, cleaned, and business-ready data layers
- Learned the concept of incremental processing and why it is essential at scale
- Understood common incremental processing patterns (timestamp-based, ID-based, change-based)
- Learned why incrementality must be applied across Bronze, Silver, and Gold layers

### Day 7 – Databricks Jobs & Workflows

- Understood the difference between Databricks notebooks and Jobs
- Learned how multi-task workflows model pipelines as dependent tasks
- Learned how parameters make jobs reusable without changing code
- Understood scheduling for automated, reliable job execution
- Learned the importance of error handling, retries, and fail-fast behaviour

### Day 8 – Data Governance & Organization

- Learned the Catalog → Schema → Table hierarchy in Databricks
- Understood access control using GRANT and REVOKE
- Learned the importance of data lineage for debugging and impact analysis
- Understood the difference between managed and external tables and when to use each

### Day 9 – Analytics with Databricks SQL

- Learned the role of SQL Warehouses for fast, isolated analytical workloads
- Understood complex analytical queries for trends, comparisons, and rankings
- Learned how dashboards present curated business insights
- Understood the role of visualizations and filters for interactive analytics

### Day 10 – Query Performance & Optimization

- Learned how query execution plans determine how SQL queries are executed
- Understood partitioning strategies for efficient data skipping
- Learned how OPTIMIZE reduces small file overhead
- Understood how ZORDER improves data skipping within partitions
- Learned when and when not to use caching for faster query performance
