# Amazon_Vine_Analysis
Analysis of amazon and vine reviews using spark and google collaborate notebook

## Overview of the analysis of the Vine program:

The purpose of this analysis is to use Spark to analyze the large set of data from amazon pet product reviews. Amazon AWS services were used to create the database, and google collaborate was used for Spark. In addition, the bias of vine reviews (a paid service) were compared to unpaid amazon reviews from the same dataset.

## Results:

- How many Vine reviews and non-Vine reviews were there?
  - There were 162 Vine reviews versus 35,568 Non-Vine reviews. There are significantly more non-Vine reviews compared to Vine reviews.
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - 63 of the Vine reviews were 5 stars wheareas 19,437 of the Non-Vine reviews were five stars.
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - About 39% of Vine reviews were 5 stars versus 55% of Non-Vine reviews being five star

## Summary:

Due to the sample sizing being so wildly out of proportion, it is difficult to say if the Vine program has any bias. With the current data, it looks like those who are part of the Vine program are less likely to give five star reviews versus those who are not in the Vine program. In summary, there does not seem to be a positivity bias for those in the Vine program. However, it could be that there are less Vine users reviewing pet products. If a more common good was chosen such as books or electronics, there might be a larger set of vine reviews to analyze. With this dataset, it may be worthwhile to analyze the entire review set instead of just five star reviews. It could be that those in the Vine program scrutinize they products they are given and more likely to give four star reviews or lower. Do Vine users give out more 1-star reviews than non-Vine users?
