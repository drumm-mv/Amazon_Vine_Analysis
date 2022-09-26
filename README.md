# Amazon_Vine_Analysis
Using Pyspark and AWS for ETL

## Overview of the analysis:
The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. In this analysis I focused on PC reviews to determine if a bias exists within the Vine reviews program.

## Results:

![image_name](/Resources/vine_review_totals.png)

After transforming the data into a dataframe containing reviews that fell within a "helpful review percentage" (helpful reviews to total reviews) threshold of 50% or higher, there was a total of 79162.
Of this total between 2-3% were from the Vine program. Total Vine reviews was 1775 and non-Vine reviews totaled 77387.

There were a total of 36732 5-star reviews, of which 783 were paid and 35949 were unpaid.

44% of Vine (paid) reviews were 5-stars while 46% of non-Vine (unpaid) reviews were 5-stars.

## Summary:

Based upon the percentages of 5-star Vine reviews and non-Vine reviews being within 2% of each other we can say that there is not a positivity bias for reviews in the Vine program.

In addition to the analysis done, we should perform a distribution analysis for all star ratings to see if the Vine reviews maintain an equal bias to non-Vine reviews.
