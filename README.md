This project involves building a batch ETL pipeline to analyze ATM transaction data for Spar Nord Bank. The data includes transaction details such as card type, location, date, time, ATM type, and transaction amount. The objective is to optimize ATM refill frequency and draw insights from the data.

Key analytical queries include identifying the top 10 ATMs with the most transactions in the 'inactive' state, analyzing ATM failures by weather conditions, determining the top 10 ATMs with the highest transaction volumes, tracking inactive ATM transactions per month, and examining failed transactions by card type.

The ETL pipeline consists of extracting transactional data from a MySQL RDS server to an HDFS instance using Sqoop, transforming the data with PySpark to match a given target schema, loading the transformed data into an S3 bucket, creating Redshift tables based on the target schema, and finally loading the data from S3 into Redshift tables.

The project aims to enhance Spar Nord Bank's understanding of ATM usage patterns and improve operational efficiency through informed decision-making based on data analysis.

