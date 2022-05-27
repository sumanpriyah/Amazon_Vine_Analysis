# Amazon_Vine_Analysis

## Overview of the analysis: 

The purpose of this analysis is to provide if the reviews written by members of the paid Amazon Vine program are baised. I have picked product category as 'Shoes' to evaluate the vine and non-vine reviews. 
I have used PySpark to perform the ETL process to extract data into pgAdmin and later used Pandas to determine if there is any bias towards favorable reviews from Vine members. The evaluation is done on helpful_votes greater than 50%. 

### Deliverables

1	Perform ETL on Amazon Product Reviews

2	Determine Bias of Vine Reviews

3	A Written Report on the Analysis (README.md)

## Results: 

### Vine reviews and non-Vine reviews 

The count of vine reviews are 22 and count of non-vine reviews are 26987.

![](https://github.com/sumanpriyah/Amazon_Vine_Analysis/blob/main/Images/Paid%20and%20unpaid%20count.png)

![](https://github.com/sumanpriyah/Amazon_Vine_Analysis/blob/main/Images/Paid_df.png)

![](https://github.com/sumanpriyah/Amazon_Vine_Analysis/blob/main/Images/unpaid_df.png)

### Vine reviews were 5 stars and non-Vine reviews were 5 stars

The count of  vine 5 star reviews are 13 and count of 5 star paid non-Vine reviews are 14475.

![](https://github.com/sumanpriyah/Amazon_Vine_Analysis/blob/main/Images/Total%205%20start%20paid%20reviews.png)

![](https://github.com/sumanpriyah/Amazon_Vine_Analysis/blob/main/Images/Total%205%20start%20un%20paid%20reviews.png)

### Percentage of Vine reviews were 5 stars and percentage of non-Vine reviews were 5 stars

The percentage of vine 5 star reviews is 59.09% and percentage of 5 star non-vine reviews is 53.64%.

![](https://github.com/sumanpriyah/Amazon_Vine_Analysis/blob/main/Images/Percentage%205%20star%20paid%20reviews.png)

![](https://github.com/sumanpriyah/Amazon_Vine_Analysis/blob/main/Images/Total%205%20start%20unpaid%20reviews.png)

## Summary: 
There are total of 22 vine reviews and non vine reviews are 26987. The count for Vine reviews is very less and 5 star Vine reviews are only 13.The percentage of 5 star vine reviews is close to non-vine reviews. 
We need more data for Vine reviews to determine the positivity bias for reviews in the vine program. we need to consider another star reviews too.
If we calculate percentage for all start total paid and unpaid reviees then total paid reviews is less than 1% and unpaid reviews are 99%. We need more data to for paid reviews in vine program.

![](https://github.com/sumanpriyah/Amazon_Vine_Analysis/blob/main/Images/All%20total%20perc.png)

