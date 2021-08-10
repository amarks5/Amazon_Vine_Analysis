# Amazon_Vine_Analysis
## Analysis Overview
In this project we are analyzing the Amazon Vine program to see if there is a bias in regards to favorable reviews for the members of Vine. We use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance and load the transformed data into pgAdmin.

## Results
### Total Number of reviews breakdown
* There were a total of 1977 Vine reviews.

 ![alt text](https://github.com/amarks5/Amazon_Vine_Analysis/blob/main/images/vine_reviews_count.PNG)
  
 * There were a total of 696,349 non-Vine reviews.

 ![alt text](https://github.com/amarks5/Amazon_Vine_Analysis/blob/main/images/non_members_reviews_count.PNG)
 
### Total Number of 5-Star Reviews
* Total Number of Vine 5-Star Reviews was 780.

![alt text](https://github.com/amarks5/Amazon_Vine_Analysis/blob/main/images/paid_five_star_review_count.PNG)

*  Total Number of Non-Vine 5-Star Reviews was 329,844

![alt text](https://github.com/amarks5/Amazon_Vine_Analysis/blob/main/images/unpaid_five_star_review_count.PNG)

### Overall Percentage of 5-Star Reviews
* Percentage of 5-Star Vine Reviews was roughly 39.5%.

![alt text](https://github.com/amarks5/Amazon_Vine_Analysis/blob/main/images/paid_five_star_percentage.PNG)

* Percentage of 5-Star Non-Vine Reviews was roughly 47.4%.

![alt text](https://github.com/amarks5/Amazon_Vine_Analysis/blob/main/images/non_members_reviews_percentage.PNG)

## Summary
When comparing the 5-star review percentages between members and non-members, non-members lead with 47.4% compared to members with 39.5%. This suggests a negative bias for reviews in the vine program. In addition, it would be beneficial to run a statistical analysis like mean, median, mode, etc.
