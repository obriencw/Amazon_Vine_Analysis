# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program
This project analyzed the product reviews information from one of the many Amazon review datasets.  The purpose of this project was to perform Extract, Transform and Load (ETL) process.  This analysis utilizes the sports data which contains the following information: unique review_id, star_rating out of 5, total amount of helpful_votes, amount of total_votes, is there a vine membership for this review, and whether or not the review was a verified_purchase  The purpose of this analysis was to determine the total number of reviews, the number of 5-star reviews, and the percentage of 5-star reviews for the two types of review (paid vs unpaid).
## Results
- From our analysis, we were able to determine that there were a total of 334 Vine reviews as evidenced by the number of rows in the table below.

![Vine Reviews](/Vine_Reviews.PNG)

- Furthermore, we were able to determine that there were a total of 61,614 non-Vine reviews as evidenced by the number of rows in the table below.

![Non-Vine Reviews](/non_vine_reviews.PNG)

- When we analyzed the data to find the number of five star vine reviews, we discovered that there were 2,961,019 five star Vine reviews.

![Vine 5 Star Reviews](/vine_five_stars.PNG)

- We analyzed the dataframe by using the code below to determine that the percentage of of 5 star reviews for paid Vine members was 39.82%.

![Vine 5 Star Percentage](/vine_percentage.PNG)

- We analyzed the dataframe by using the code below to determine that the percentage of of 5 star reviews for Non-Vine members was 51.62%.

![Non-Vine 5 Star Percentage](/nonvine_percentage.PNG)
## Summary
If there was any positivity bias for reviews in the Vine program, we would expect the percentage of 5-star reviews to be higher for paid Vine members than for non-Vine members.  Reviewing the results of our analysis reveals that the percentage of 5-star reviews was actually higher for non-Vine members than it was for Vine members.  For this reason, we claim that there is no positivity bias for reviews in the Vine program.  To further support this statement, an additional analysis that we could perform would be to compare the average of all Vine ratings to the average of all the non-Vine ratings; if the average rating was higher for non-Vine members then we could further support our claim that there is no positivity bias for reviews in the Vine program.