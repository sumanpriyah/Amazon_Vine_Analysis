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

!["Scores as nan"](https://github.com/sumanpriyah/School_District_Analysis/blob/main/Images/replacing%209th%20grade%20scores/Average%20score%20by%20grade%20per%20school.png)

### Vine reviews were 5 stars and non-Vine reviews were 5 stars

The count of  vine 5 star reviews are 13 and count of 5 star paid non-Vine reviews are 14475.

### percentage of Vine reviews were 5 stars and percentage of non-Vine reviews were 5 stars

The percentage of vine 5 star reviews is 59.09% and percentage of 5 star non-vine reviews is 53.64%.


## Summary: 
There are total of 22 vine reviews and non vine reviews are 26987. The count for Vine reviews is very less and 5 star Vine reviews are only 13.The percentage of 5 star vine reviews is close to non-vine reviews. 
We need more data for Vine reviews to determine the positivity bias for reviews in the vine program. we need to consider another start reviews 

