# CUSTOMER SEGMENTATION

Customer segmentation using unsupervised clustering (Agglomerative Clustering)

## Description

Implementing unsupervised clustering which is agglomerative clustering. Customer segmentation is the practice of separating customers into groups that reflect similarities among customers in each cluster. I will divide customers into segments to optimize the significance of each customer to the business. To modify products according to distinct needs and behaviors of the customer. It also helps the business to cater to the concerns of different types of customers.

## Table of contents

* 1. IMPORTING LIBRARIES
* 2. LOADING DATA
* 3. DATA CLEANING
* 4. DATA PREPROCESSING
* 5. DIMENSIONALITY REDUCTION
* 6. CLUSTERING
* 7. EVALUATING MODELS
* 8. PROFILING
* 9. CONCLUSION
* 10. END

## Conclusion

### There are 4 cluster:
* cluster 0 : high spending & average income
* cluster 1 : low spending & average income
* cluster 2 : low spending & low income
* cluster 3 : high spending & high income

### Profiling the 4 clusters:

__Abouts cluster number: 0__
* definitely a parent
* max have 3 members in the family size, and min have 2
* most have teenager at home
* relatively older
* high spending and average income

__Abouts cluster number: 1__
* definitely a parent
* definitely have kids
* max have 5 member  in the family size, and min have 3
* relatively older
* low spending and average income

__Abouts cluster number: 2__
* mostly a parent
* have subset of not a parent
* have 3 members in the family size, and min have 1
* range of age wery wide, between 20 - 80 year old
* low spending & low income

__About cluster number: 3__
* definetily not a parent
* max have 2 member in the family size, and min have 1
* range of age wery wide, between 20 - 80 year old
* high spending and high income

### Another conclusions
* cluster 3 is the biggest set of customers closely followed by cluster 0
* Campaign did not work very well. Very few participants overall in promotions campaign.
* Perhaps better-targeted and well-planned campaigns are required to boost sales.
* Unlike campaigns, the deals offered did well. It has best outcome with cluster 1 and cluster 0.
* However, our star customers cluster 3 are not much into the deals
