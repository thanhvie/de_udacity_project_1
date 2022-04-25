# Sparkify purpose
- The purpose of this design is to create a database which can optimize queries on song play analysis
# How to run Python scripts with Jupiter Notebook
### Step 1: Create database tables
```
%run -i 'create_tables.py'
```
### Step 2: Run the ETL script
```
%run -i 'etl.py'
```
# An explanation of the files in the repository
- data: data folder which contains song_data and log_data
- create_tables.py: script to create database tables
- sql_queries.py: script contains all sql queries using in the project
- etl.py: script to run ETL pipeline
- etl.ipynb: contains detailed instructions on the ETL process for each of the tables
- test.ipynb: use for test
# State and justify
- The database schema design and ETL pipeline are implemented correctly from project requirements