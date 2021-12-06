# Amazon_Vine_Analysis

## Overview
The purpose of this project is to analyze the Amazon Vine program and determine whether there is a bias towards positive reviews.
Using PySpark to perform ETL, the analysis extracts the dataset, transforms the data, connects to an AWS RDS instance, loads the transformed data into pgAdmin. 

## Deliverable 1: Perform ETL on Amazon Product Reviews

Using my knowledge of the cloud ETL process, I created an AWS RDS database with tables in pgAdmin,  I make use of a dataset from the [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Video_Games_v1_00.tsv.gz) and extract the dataset into a DataFrame. Then, transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, I upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded. 

![dev1](https://user-images.githubusercontent.com/58860105/144785492-89a30098-ea82-4f0b-bbc9-0bf42790cbe3.PNG)


![dev1 1](https://user-images.githubusercontent.com/58860105/144785567-b29ca371-e4bf-4023-995a-ad8ef593dc9b.PNG)



## Deliverable 2: Determine Bias of Vine Reviews

Using my knowledge of PySpark, Pandas, or SQL, I determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, also determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

### Results: 

Paid Vine Reviews

![paid](https://user-images.githubusercontent.com/58860105/144790586-75a193dd-bd21-4782-af9e-f3482392d723.PNG)

Unpaid Vine Reviews

![unpaid](https://user-images.githubusercontent.com/58860105/144790815-728d75ce-1485-4113-8d69-fcf7ab0c768e.PNG)




![paidere](https://user-images.githubusercontent.com/58860105/144791822-e1f8f6e7-c1f4-45f2-9f65-9ad7b6e8ff10.PNG)


![unpai2d](https://user-images.githubusercontent.com/58860105/144791893-a320ed14-2d2b-4ff5-b976-186f6648989e.PNG)



## Summary

## Resources

* Dataset:[Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Video_Games_v1_00.tsv.gz)
* Software: PostgreSQL, pgAdmin, AWS (RDS, S3), Google Colab. 

