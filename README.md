#### Overview of SQL functions that I've used

**Point of Document:** The purpose of this document is to outline the common SQL queries I've used to pull data, create tables/views, ctes, etc. Although queries do get more complex than this, these are the highlevel ones that I use on a daily basis. 

*Outlining the following:*
- pulling in data using spark - using spark.sql() function to properly use SQL scripts in python
- Subqueries - joining onto a dataset by using it as a filter (inner join) and/or to figure out aggregates and partioning.
- CTEs - Creating a common table expression to either filter (inner join) and/or to figure out aggregates and partitions.
- Where, Having, and Case statements - Statments that end up filtering the data in some format.
- Aggregate / Window functions - SUM and Row number partitioning
- Creating tables / views in SQL
- Aggregates - SUM, AVG, COUNT, COUNT(DISTINCT())
- LIMIT - To get a snapshot of the table
