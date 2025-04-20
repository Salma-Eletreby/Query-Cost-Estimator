# Query-Cost-Estimator
Java Swing application connected to MySQL to estimate query cost based on execution plans.

## Project Overview

This project involves creating a **Query Cost Estimator** that estimates the execution costs of SQL SELECT and JOIN queries.

The application is designed to interact with a relational database schema, analyze queries (SELECT and JOIN operations), and generate execution plans with estimated costs. The estimator uses metadata and statistics about the database schema and tables to determine the optimal query execution plan.

### Features
- Accepts SQL queries involving SELECT and JOIN operations.
- Supports SELECT operations on primary and non-primary keys with equality and range operators.
- Supports JOIN operations for equi-joins.
- Generates a list of possible execution plans with estimated costs.
- Displays statistics associated with the relations involved in the queries.

### Metadata and Statistics
- Metadata for tables: Each table will store essential information such as the number of rows, index availability, page size, etc.
- Query cost estimation will be based on these statistics to determine the most efficient query plan.


## Utility Functions

- Display statistics: The application will allow users to view metadata and statistics for the tables involved in the query.