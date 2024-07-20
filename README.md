# Customer Segmentation

## Problem Statement
Identify different customer groups based on their purchasing habit. Create subsets of a market based on demographics behavioural criteria to better understand the target for marketing activities. Segmentation is a great way to identify marketing groups and design business strategies around it accordingly.

## Performing EDA

1. The mean and median are very close for annual income so we can guess it is a normal distribution.
2. All variables have normal distributions.
3. Majority of spending score is isolated between 40-50.
4. Female portion is more frequent.
5. Age highest frequency- 30-40 female
6. Median age is higher for males and a larger section.
7. Spending score is similar for both
8. ![Screenshot 2024-07-20 142542](https://github.com/user-attachments/assets/5fcc4d13-461d-4fa7-9fa3-53957c3fd6b4)

Age is similar
Annual income of male is slightly higher
Spending score of fem is slightly higher


## Use Kmeans cluster algorithm
1. Used the elbow method to estimate the best number of clusters.
2. Our ideal cluster is dominated by females (53% with an average age of 32)
3. Custer 3 have low income but high spending score with average age 25. 

![kmeans](https://github.com/user-attachments/assets/02095823-7f96-4b8c-a7b0-b37ca884c667)

## Analysis

1. Cluster 2 should be maine focus as they have high income and high spending score. Should take advantage of the fact that 53% od these are women.
2. Cluster 3 presents an interesting opportunity to market to the customers for sales event on popular items. 
