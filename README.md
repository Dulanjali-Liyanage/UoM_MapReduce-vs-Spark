# UoM_MapReduce-vs-Spark

This repository contains the files to compare and contrast MapReduce and Spark using a given set of data.

Steps followed
1. Create an AWS EMR cluster with Hadoop, Hive and Spark installed
2. Create an AWS S3 bucket and upload the provided csv file for analysis
3. Connect to EMR through SSH
4. Run the commands to connect to Hive client and create an external table to store the values gained from the above uploaded csv file. Then run the hiveql queries in the Hive-Queries.sql to see the execution time for each result.
5. Exit from the hive client.
6. Connect to Spark SQL service. (Do not need to create a table as we have already did it in the above steps). Next run the spark sql queries in Spark-Queries.sql file and see the execution time for each result.
7. Compare and contrast those values.
