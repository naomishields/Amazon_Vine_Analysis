# Amazon Vine Analysis

## Overview 
The purpose of this analysis was to analyze a set of data made up of amazon reviews. First a dataframe with just reviews with at least 20 votes was put together. Then after finding which reviews had more thna 20 votes it was further filtered to only reviews with more than half of the votes being helpful votes. After that it was broken into two separate dataframes, one for vine (paid) users and one for non-vine users. Finally, after breaking it into the two dataframes, both dataframes were analyzed to determine whether or not there was bias in the way that vine users reviewed products.

## Results 
![Vine Reviews](https://github.com/naomishields/Amazon_Vine_Analysis/blob/main/Resources/vine_reviews.png)
![Non-Vine Reviews](https://github.com/naomishields/Amazon_Vine_Analysis/blob/main/Resources/non_vine_reviews.png)
The pictures above show the analysis for the Vine users vs. the non-Vine users.

Based on this information, we can answer a few questions:
* How many Vine reviews and non-Vine reviews were there?

  *There were 19 Vine reviews and 8,332 non-Vine reviews*
  
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? 

  *There were 9 five star Vine reviews and 4,783 non-Vine five star reviews*
  
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

  *47.4% of Vine reviews were five stars and 57.4% of non-Vine reviews were five stars*
  
## Summary 
Based on the analysis, there does not appear to be any positivity bias for reviews in the Vine program. The non-Vine users actaully received more five star reviews. An additional that would be interesting is to look at the mean star ratings for Vine users and non-Vine users. This would provide the average rating for the two groups and we could see whether or not there was much of a difference. 
