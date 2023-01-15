# Amazon_Vine_Analysis
Understanding Big Data and applying PySpark, Hadoop, AWS and SQL databases in analyzing amazon reviews for a company

## Overview 
The purpose of this project was to assist a company interested in enrolling in the amazon vine program determine if it's worth the cost. The vine program provides free products to select consumers and require them to publish reviews on the products. The analysis involves gathering data, performing ETL using PySpark, AWS, SQL and Pandas on the data to determine if there is actually any bias in the product reviews given by the vine (paid) members versus the non-vine (unpaid) members.

## Results

![img](https://github.com/SNwokolo/Amazon_Vine_Analysis/blob/673d102237d5a2e7e721e3ffab7fa28db7cd41f8/Dataframes.png)

- The total number of vine reviews obtained from this dataset was 47 while that of the non-vine reviews was 8362.
- The number of 5-star vine reviews was 15 while that of the non-vine reviews was 4332.
- 31.9% of the vine reviews were obserbed to be 5-star ratings and for the non-vine reviews, the percentage was 51.8%

![img](https://github.com/SNwokolo/Amazon_Vine_Analysis/blob/673d102237d5a2e7e721e3ffab7fa28db7cd41f8/Calculations.png)  


## Summary
From the results observed above on this particular dataset, it is safe to say that there was no positivity bias observed for the reviews of the vine program members. The product had significantly more total reviews from consumers who were not a part of the vine program, more than half of the reviews for the non-vine consumers(51.8%) were also observed to be 5-star ratings compared to those of the vine members (31.9%).
One additional analysis that could be done on the dataset to support this would  be using the amount of reviews for the product and the amount of verified purchases to determine if there is any difference between those given the product to review and those who purchased the products on their own.