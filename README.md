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
   
   
      ![Total number of vine reviewers](https://user-images.githubusercontent.com/71282697/105655089-431b1e00-5e74-11eb-932a-1144a96004f6.png)

   - non-Vine reviews
   
 
      ![Total number of non-vine reviewers](https://user-images.githubusercontent.com/71282697/105655175-6ba31800-5e74-11eb-92f2-3b88d6fda77b.png)
 
 
 - Total number of 5-star reviews
 
   - Vine reviews
   
  
      ![Total number of 5-star vine reviewers](https://user-images.githubusercontent.com/71282697/105655243-8d040400-5e74-11eb-9c98-1b49da03666c.png)
     
     
    - non-Vine reviews
  
  
      ![Total number of 5-star non-vine reviews](https://user-images.githubusercontent.com/71282697/105655318-b6bd2b00-5e74-11eb-950e-e5fb519494ee.png)
     
  
  - Percentage of 5-star reviews
  
    - Vine reviews
   
     ![The percentage of 5-star vine reviews](https://user-images.githubusercontent.com/71282697/105655455-ee2bd780-5e74-11eb-9f7e-35a9477b6e50.png)
   
    - non-Vine reviews
   
     ![The percentage of 5-star non-vine reviews](https://user-images.githubusercontent.com/71282697/105655599-2f23ec00-5e75-11eb-9cac-f9e2a612deae.png)
   
   
   ## Summary
 
 
