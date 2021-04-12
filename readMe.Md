# Project - Data Modeling with Apache Cassandra

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

# Creating an E
The startup would like to create a pipeline to ETL the CSV data to a No SQL database - specifically Apache Cassandra.
Creating a No SQL database has a number of advantages like dealing with larger data sets because it is denormalized. The downside of using denormalized data model is that we will have duplicate fields in multiple fields. However, the amount of processing power is greatly reduced because we won't and can't utilize joins in Apache Cassandra.

We 