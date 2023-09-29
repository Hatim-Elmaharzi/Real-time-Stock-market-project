# Real-time-Stock-market-project
## INTRODUCTION  
In this project, we took some stock market data, we used python to produce that data and put it into kafka cluster  
After that, we consumed that data and store it into amazon s3, we crawl that data to build a catalog and analyse  
that data in aws athena using sql to get useful insights.  
Here are the major steps that guide our project:  
  
## STEPS:  
1-Creating an ec2 machine in our aws account -sc1  
2-Downloading Apache Kafka in ec2 -sc2  
3-Start Zoo-keeper -sc3  
4-Start Kafka server sc4  
5-Start the producer after creating the topic and associate it to jupyter file producer -sc5  
6-Start the consumer and associate it to jupyter file consumer -sc6  
7-stock the data into aws s3 bucket -sc7  
-----------The data follows the following path: Indexprocessed(a CSV file on my local machine) -> producer -> consumer -> S3 bucket (each record as a JSON file).---------  
8-Discover and catalog metadata about data stored in s3 bucket -sc8  
9-Storeing information about the data discovered by the crawler in data catalog -sc9  
10-Analysing data by running SQL queries on the data stored as columns and rows in amazon athena -sc10  
  
## Technology used:  
Apache Kafka  
Python/Jupyter  
AWS S3  
Amazon Athena  
AWS Glue Crawler  
AWS Glue Catalog  
AWS EC2  
  
### All screens in screen file  
