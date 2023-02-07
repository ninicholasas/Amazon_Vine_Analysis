# Amazon_Vine_Analysis

## Overview of Analysis
The purpose of this project is to analyze the product reviews for the Amazon Vine program. The data was obtained from [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt). I used PySpark in Google Colab to transform the data and uploaded to the AWS hosted PostgreSQL database.

I chose __amazon_reviews_us_Wireless_v1_00.tsv.gz__ for this analysis.
## Results

<img width="387" alt="image" src="https://user-images.githubusercontent.com/110373282/217386860-9f58e285-735e-4120-976e-3162ff9197a7.png">

### Paid
* Total reviews: 613
* Total 5-star reviews: 222
* Percentage of 5 -star reviews: 36.22%

### Unpaid
* Total reviews: 64,968
* Total 5-star reviews: 30,543
* Percentage of 5 -star reviews: 47.01%

## Summary
