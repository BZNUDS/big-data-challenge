# My big-data-challenge Homework 
aka Big Data Homework #22 - "Alexa, can you handle big data?"


I uploaded my code and associated file to the following location on GitHub: https://github.com/BZNUDS/big-data-challenge

My Amazon S3 Buucket "bigdatas3v2public" can be found at https://s3.console.aws.amazon.com/s3/buckets/bigdatas3v2public?region=us-east-2&tab=objects

My Amazon RDS Database "rdsdb" can be found at https://us-east-2.console.aws.amazon.com/rds/home?region=us-east-2#databases:


My SQL Querries can be found at https://github.com/BZNUDS/big-data-challenge/blob/main/SQL%20querries.sql



For this Homework Assignment, I created a new repository for this project called big-data-challenge and then cloned the new repository to my computer.

Inside my local git repository, I created a directory for the level-1 challenge that I chose. (If time permits I will try to add more, BUT it is optional and I feel I submited A+ content (again).

Downloaded a Google Colab Notebook as a ipynb file and add it to this folder. Then as requested, created two different files (one for each Dataset I used from Amazon.)

Added code to make it my main script to run for analysis. I added a file with my SQL querries to my repo.

Pushed the above changes to GitHub as noted above.



Background
In this assignment I put my ETL skills to the test...but had fun doing it. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. Your first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.
There are two levels to this homework assignment. The second level is optional but highly recommended.

Create DataFrames to match production-ready tables from two big Amazon customer review datasets.
Analyze whether reviews from Amazon's Vine program are trustworthy.


Instructions

Level 1

Used the furnished schema to create tables in your RDS database.

Created two separate Google Colab notebooks and extract any two datasets from the list at review dataset, one into each notebook.
Note: It is possible to ETL both data sources in a single notebook, but due to the large data sizes, it will be easier to work with these S3 data sources in two separate Colab notebooks.

Believe I handled the header correctly. If you read the file without the header parameter, you may find that the column headers are included in the table rows.

For each notebook (one dataset per notebook), complete the following:

Count the number of records (rows) in the dataset.

Transform the dataset to fit the tables in the schema file. Be sure the DataFrames match in data type and in column name.

Load the DataFrames that correspond to tables into an RDS instance. Note: This process can take up to 10 minutes for each. Be sure that everything is correct before uploading.

I think it went well and I really enjoyed doing it. But please reach our to me via Slack or email if there is any questions or concerns.

Thank you,

Brian Zdarsky
