### Capstone: Credit Card Customer Segmentation with Unsupervised Learning
**Tools: Python, pandas, scikit-learn (K-Means, PCA), Matplotlib, Seaborn** | M.S. Data Analytics Project (D214 - Capstone)

For my master's capstone, I tested whether 8,950 credit card holders could be grouped into distinct behavioral profiles from six months of transaction data. I set a formal, measurable success threshold before modeling and reported the results against it, even when the model fell short.
 
- Framed the research as a hypothesis test with a silhouette score threshold of 0.5 defining "well-separated" customer segments
- Handled missing values with logic tied to customer behavior, setting minimum payments to zero for inactive accounts and using medians elsewhere to preserve each feature's distribution
- Selected three clusters using the elbow method and silhouette analysis, then used PCA to reduce 18 features to two dimensions for visual validation
- Profiled three segments (engaged high spenders, low-engagement cautious users, and cash-advance-reliant revolvers) and translated each into a targeted strategy
- Reported a silhouette score of 0.25, failed to reject the null hypothesis, and documented why K-Means assumptions likely limited separation, recommending DBSCAN and Gaussian mixture models as next steps

[Documentation](https://github.com/hrbergman/postgresql-customer-services-query/blob/main/postgresql-customer-services-query/data-acquisition-documentation.pdf)
| 
[Video Presentation](https://youtu.be/jKOE0cG68rc)
