# Amazon Vine Reviews Analysis: Pet Products


## Overview: 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products by paying a fee to Amazon who, in turn, provides products to Amazon Vine Members. In return for receiving the product free of charge, Amazon Vine members are required to publish a review on the Amazon Online Store. 

The purpose of this analysis was to evaluate whether or not reviews written by Amazon Vine members revealed any bias toward favorable reviews, or more specifically, a higher percentage of 5-star reviews. 

We analyzed Amazon reviews of **Pet Products**.


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

Analysis of the **Pet Products** data set revealed the following:

- There were only 170 Vine member reviews versus 37,840 non-Vine member reviews. 
- Out of the 170 Vine reviews, there were only 65 5-star reviews. 
- Out of 37,840 non-Vine reviews, there were 20,612 5-star reviews. 
- This translates into approximately 38% of Vine reviews being 5-star reviews while approximately 54% of non-Vine reviews were 5-star reviews. 



## Summary: 

- Based on these results, I don't have sufficient evidence to determine if positivity bias exists for Amazon Vine reviews of pet products. While at first glance, it appears that there is no positivity bias from the Amazon Vine reviewers based on a lower percentage of 5-star reviews (38%), there were so few Amazon Vine reviews that it is hard to make this determination. 
- In our Pet Products category, the Amazon Vine reviewers didn't even account for 1% of all reviews we analyzed after filtering the data for helpful reviews. 
- It is interesting to note that 54% of the non-Vine reviews were 5-star reviews, which may lend additional evidence against positivity bias among Vine members. 
- Additional analysis that could prove helpful in evaluating for positivity bias amongst Vine members would be analyzing a different data set in the same fashion. Perhaps a different product category with more Amazon Vine members reviewing products would yield different results.   
