# Amazon Vine Analysis

## Overview of Analysis

### Purpose
The main purpose of this analysis was to determine whether or not Amazon Vine program members are more biased to leave favorable reviews of Amazon products than customers who are not members of that program. This analysis was done by extracting videogame review data from Amazon and filtering the data to create 2 separate tables: one for videogame reviews left by Vine program members and one for videogame reviews left by non_Vine reviewers. The percentage of 5-star reviews from both tables were compared to see if Vine program members are indeed more likely to leave 5-star reviews than non_Vine reviewers.

## Results

### Figure 1: Videogame Reviews Left by Amazon Vine Program Members (First 20 Rows)
![](https://github.com/HannaKim4673/Amazon_Vine_Analysis/blob/main/Images%20for%20readme/figure%201.png)

### Figure 2: Videogame Reviews Left by Unpaid Reviewers (First 20 Rows)
![](https://github.com/HannaKim4673/Amazon_Vine_Analysis/blob/main/Images%20for%20readme/figure%202.png)

- Total Review Count Comparison
  - 94 reviews were left by Amazon Vine program members
  - 40,471 reviews were left by non-Vine, or unpaid, reviewers
- 5-star Review Count Comparison
  - 48 of the 94 Vine reviews were 5-star reviews
  - 15,663 of the 40,471 non-Vine reviews were 5-star reviews
- 5-star Review Percentage Comparison
  - about 51.06% of the Vine reviews were 5-star reviews
  - about 38.70% of the non-Vine reviews were 5-star reviews
  - This gap in the number of 5-star reviews left by the two groups is not too surprising, given that there are more 5-star reviews in Figure 1, which shows the first 20 rows of data for reviews left by Amazon Vine members, than in Figure 2, which shows the first 20 rows of data for reviews left by non-Vine reviewers.

## Summary
All in all, it would appear that there is positivity bias for reviews in the Vine program. After all, as mentioned in the previous section, Amazon Vine program members left about 12.36% more 5-star reviews for videogames sold by Amazon than non-Vine reviewers. Also, comparing Figure 1 and Figure 2, there are definitely more 5-star reviews in Figure 1, which shows the first 20 rows of data for reviews left by Amazon Vine members, than in Figure 2, which shows the first 20 rows of data for reviews left by non-Vine reviewers. Another analysis that could be done with this dataset that would support my finding is to compare the number of Vine reviews that were also verified purchases with the number of non-Vine reviews that were also verified purchases. It seems that many of the Vine reviews also happened to not be associated with verified purchases, which is rather odd and something worth investigating.
