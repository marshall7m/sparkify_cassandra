# Project: Data Modeling with Cassandra

## Introduction Scenario
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.


## Description
In this project, I applied what I've learned on data modeling with Apache Cassandra and complete an ETL pipeline using Python. Given that Apache Cassandra is a NoSQL database platform, I created the tables to reflect the queries that will be executed on the tables. The ETL pipeline transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

## Datasets
The dataset consist of a directory of user activity CSV files. The CSV files are partitioned by date. Here are examples of filepaths to two files in the dataset:

event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv

## ETL Pipeline

- Process event_datafile_new.csv dataset to create a denormalized dataset
- Model tables to the example queries
- Load data into tables in Apache Cassandra and validate example queries