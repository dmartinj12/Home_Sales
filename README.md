# Home_Sales

Summary
In this assignment, we leverage PySpark to analyze a home sales dataset using SQL queries and Spark operations. The primary goal is to understand how caching, partitioning, and querying large datasets affect performance. We begin by loading the dataset and answering several analytical questions using Spark SQL. We then experiment with caching and partitioning data, comparing query performance with cached versus uncached data. The data is saved in Parquet format for optimized querying, and temporary tables are created to streamline our analysis.

Key tasks include:

Loading and querying data with Spark SQL
Analyzing home prices based on specific criteria (e.g., number of bedrooms, square footage)
Caching and partitioning data to optimize performance
Measuring and comparing the runtime of cached and uncached queries
Saving the processed data in Parquet format for future use
The final deliverable is a Jupyter notebook demonstrating the entire process, from loading the data to optimizing and analyzing the results.