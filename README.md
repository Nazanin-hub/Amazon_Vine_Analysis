# Amazon_Vine_Analysis
Analyzing Amazon reviews using PySpark

## Project Overview

analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.
Then, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in my dataset.

## Resources

Data Source: Amazon Review datasets, amazon_reviews_us_Outdoors_v1_00.tsv
Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results

 - Total number of reviews
 
   - Vine reviews
   
   - non-Vine reviews
 
 ![Total number of reviewers](https://user-images.githubusercontent.com/71282697/105648984-16aad600-5e63-11eb-8e18-5cc9b729b226.png)
 
 
 - Total number of 5-star reviews
 
   - Vine reviews
  
  
  - non-Vine reviews
  
  
  - Percentage of 5-star reviews
  
   - Vine reviews
   
   - non-Vine reviews
   
   ## Summary
 
 
