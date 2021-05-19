# Data_Modeling_with_Apache_Cassandra

## Project Background
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app. As a data engineer my job was to create an Apache Cassandra database which can create queries on song play data to answer the questions. 

## Project Overview
With this project I applied data modeling with Apache Cassandra and completed an ETL pipeline using Python.  

## Datasets
For this project, I worked with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:
`event_data/2018-11-08-events.csv`
`event_data/2018-11-09-events.csv`

## Project Steps
Below are steps of this project:
### Modeling NoSQL database or Apache Cassandra database
1.	Design tables to answer the queries outlined in the project template
2.	Write Apache Cassandra `CREATE KEYSPACE` and `SET KEYSPACE` statements
3.	Develop `CREATE` statement for each of the tables to address each question
4.	Load the data with `INSERT` statement for each of the tables
5.	Include `IF NOT EXISTS` clauses in `CREATE` statements to create tables only if the tables do not already exist. 
6.	Test by running the proper select statements with the correct `WHERE` clause

