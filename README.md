# Stock-Market-Project-Using-Kafka
## Description: 
In this data engineering project I wrote a code for the producer part to process the data and consumer code to read 
the processed data from producer into AWS S3 bucket. Used AWS crawler to traverse the entire schema from the S3 bucket 
so that it can be queried using AWS Athena. The command_kafka.txt is for reference of commands used to start the 
zoo-keeper services and the kafka-server at the same time it also has commands to create a topic in kafka and the
commands for starting the producer and consumer.

## Technologies Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka

## Dataset Used
Here is the dataset used - https://github.com/Jeson-Antony/Stock-Market-Project-Kafka/blob/main/indexProcessed.csv
