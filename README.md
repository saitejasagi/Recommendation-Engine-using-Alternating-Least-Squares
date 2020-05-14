# Recommendation-Engine-using-Alternating-Least-Squares
Building a Recommender System based on Collaborative Filtering on Yelp Reviews dataset using Spark

**Model**

Collaborative Filtering is a method of making predictions about the interests of a user by learning their preference based on information of their engagement with a set of available items, along with other users’ engagements with the same set of items. In the more general sense, it is the process of filtering for information or patterns using techniques involving collaboration among multiple agents, viewpoints, data sources, etc. Alternating Least Square (ALS) is a matrix factorization algorithm and it runs in a parallel fashion. ALS is implemented in Apache Spark ML and built for a larges-scale collaborative filtering problems. ALS is perhaps the most suited method to solve scalability and sparseness of the ratings data, and it’s simple and scales well to very large datasets. ALS works by Matrix Factorization Algorithm. Matrix Factorization decomposes a large matrix into products of matrices optimizing each at a time.

**Results**

Latent Vectors	15	10	15	15	15
Iterations	10	10	20	20	20
Reg Parameter	0.01	0.01	0.001	0.05	0.01
RMSE	1.5	0.88	1.4	1.21	1.12

The lowest RMSE is observed with the following hyper parameters: 10 latent vectors, 10 iterations and  reg parameter of 0.01.


**Data**

Click on the following link https://www.kaggle.com/yelp-dataset/yelp-dataset and download the data.

**References**

1) Datacamp

