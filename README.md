# Amazon Vine Program Analysis: Pet Products


## Overview: 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products by paying a fee to Amazon who, in turn, provides products to Amazon Vine Members. In return for receiving the project free of charge, Amazon Vine members are required to publish a review on the Amazon Online Store. 

The purpose of this analysis was to evaluate whether or not reviews written by paid Amazon Vine members translated into positivity bias (i.e. higher percentage of 5-star reviews). 

## Summary of Project Phases: 

- The first phase of this project involved selecting a dataset from the Amazon Review datasets publicly available on Amazon's AWS Simple Cloud Storage (S3) solution. 
- We chose to analyze Amazon reviews of **Pet Products**

## Data Set URL
[Amazon AWS S3](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz)

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.




## Results: 

Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Summary: 

In your summary, 
- state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. 
- Then, provide one additional analysis that you could do with the dataset to support your statement.
