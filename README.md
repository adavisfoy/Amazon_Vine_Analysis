# Amazon Vine Reviews Analysis: Pet Products


## Overview: 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products by paying a fee to Amazon who, in turn, provides products to Amazon Vine Members. In return for receiving the product free of charge, Amazon Vine members are required to publish a review on the Amazon Online Store. 

The purpose of this analysis was to evaluate whether or not reviews written by Amazon Vine members revealed any bias toward favorable reviews, or more specifically, a higher percentage of 5-star reviews. 

We analyzed Amazon reviews of **Pet Products**.


## Data Set URL
[Amazon AWS S3](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz)


## Summary of Project Phases: 

- The first phase of this project involved selecting a dataset from the Amazon Review datasets publicly available on Amazon's AWS Simple Cloud Storage (S3) solution. 
- We then utilized Google's Colaboratory and PySpark to perform the ETL process as follows: 
  - Extracted the dataset from AWS S3 into Google Colaboratory
  - Transformed the Amazon Pet Products data into PySpark DataFrames and created 4 DataFrames to match tables we created in pgAdmin
  - Connected to the AWS RDS instance
  - Loaded each Dataframe into the appropriate table in pgAdmin
  - Validated that the data was loaded into pgAdmin appropriately
- The next phase involved exporting a csv file of the "Vine" table and then loading that data into Pandas for analysis within Jupyter Notebook  


## Results: 

Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Summary: 

In your summary, 
- state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. 
- Then, provide one additional analysis that you could do with the dataset to support your statement.
