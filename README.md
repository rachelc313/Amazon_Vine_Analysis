# Amazon_Vine_Analysis

## Overview of the Analysis
The purpose of the anaylsis is to use AWS, Google Colab, PgAdmin, and Pandas to provde an analyses of data retrieved from a s3 bucket for Amazon reviews on pet products. "Vine" reviews were reviews that the customer received compensation for their review. The following questions were answered:

 - How many Vine reviews and non-Vine reviews were there?
 - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Results
An analysis of the data shows that:

- There were 170 total Vine reviews.
1
The above image shows the python code used in jupyter notebook to calculate the total number of paid/Vine reviews.

- There were 65 five-star Vine reviews.
2
The above image shows the python code used in jupyter notebook to calculate the number of five-star paid/Vine reviews.

- 38% of the total Vine reviews were five-star reviews.
3
The above image shows the python code used in jupyter notebook to calculate the percentage of five-star paid/Vine reviews.

- There were 37,840 total non-Vine reviews.
4
The above image shows the python code used in jupyter notebook to calculate the total number of unpaid/non-Vine reviews.

- There were 20,612 five-star non-Vine reviews.
5
The above image shows the python code used in jupyter notebook to calculate the number of five-star unpaid/non-Vine reviews.

- 54% of the total non-Vine reviews were five-star reviews.
6
The above image shows the python code used in jupyter notebook to calculate the percentage of five-star unpaid/non-Vine reviews.

 ## Summary
The analysis shows that a higher percentage of non-Vine reviews, 54%, were five-star ratings, as opposed to the Vine reviews with 38%. This information does not support the assertion that there is any positivity bias for reviews in the Vine program. 

 I would want to perform further analysis on the dataset to fuly investigate the assertion. Filtering the data to "Verified Purchases" would be important to be able to have a certain conclusion.