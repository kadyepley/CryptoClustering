# CryptoClustering
## Objective:
- Using my knowledge of Python and unsupervised learning, I will predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Questions answered:

What is the best value for k using the original scaled DataFrame?

**Answer: The best value is 4.**

What is the total explained variance of the three principal components?

**Answer: 89.5%**

What is the best value for `k` when using the PCA data?

**Answer: The best value is 4.**


Does it differ from the best k value found using the original data?

**Answer: No, both plots show the bend in the elbow curve at 4.** 

## Final Observations:

After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

**Answer:**
  
**1. Elbow Curves:**

  The inertia in the PCA data's elbow curve is lower than in the original data's elbow curve. This indicates that the data points in the PCA data's clusters plot will be more compact, suggesting better performs in clustering the data. 
  
**2. Cluster Scatter Plots:**
  
  In the original data's clusters plot the data points are spread out and the area each prediction overlaps with other colors. This means that patterns or differences between the data points have not been completely explained in a way that properly groups them closely together.
  
  The opposite is the case with the PCA data. The clusters are better defined and there is a clearer pattern in the data. This suggests that using fewer features results in clearer and more successful clusters.
