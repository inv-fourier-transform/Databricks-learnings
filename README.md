## Databricks-learnings
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


