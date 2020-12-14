# Amazon_Vine_Analysis
## Module 16 Challenge - Analysis of Vine US Sports Goods Reviews
### Overview
Objective of this analysis is to understand if there is any bias between Vine reviews of goods between paid and unpaid Vine reviewers.

Dataset used was https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz

### Results
Using PySpark in Goggle Colaboaratory the dataset was loaded and cleaned to extract the following information:
- Based on 485,360 US reviews of Sporting Goods purchase reviews in vine
- 67,855 were analysed because they had at least 20 votes
- Of those 67,855, 61,948 were used as they had at least 50% helpful votes by other users
- Of those helpful reviews, only 334 were by paid vine users and 139 were 5 Star rating or 41.6% of reviews
- The remaining 61,614 helpful reviews were by unpaid users, of which 32,665 reviews were 5 Star or 53% of reviews

### Summary
Although there appears to be about a 12% differential between paid and unpaid subscriber reviews, the relative sparse number of paid reviewers is a fraction of a percent in relation to the unpaid reviewers, it is difficult to draw any diffinitive conclusion from the data provided.

A recomendation is to further the analysis would be to find certain reviewed items that have a significant amount of vine paid user reviews in relation to unpaid users so as to perform a more evenhanded analysis to see if there is enought to perform a bias analysis with some statistical rigour.



