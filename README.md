 # AWS Glue ETL Pipeline for Batch Processing from S3 to Redshift

This project sets up an ETL (Extract, Transform, Load) pipeline using AWS Glue for batch processing data from Amazon S3 to Amazon Redshift.

## Overview

The ETL pipeline consists of the following components:

1. **AWS Glue Job**: A Glue job written in Python that extracts data from S3, performs necessary transformations, and loads it into Redshift.
2. **AWS Glue Connection**: A connection between Glue and Redshift to facilitate data transfer.
3. **AWS Glue Crawler**: A Glue crawler to automatically discover the schema of the data stored in S3.
4. **AWS Redshift Cluster**: An Amazon Redshift cluster for storing the processed data.
   
