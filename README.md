# Recommender systems using python

Recommender systems in python using the [MovieLens 20M Dataset](https://grouplens.org/datasets/movielens/20m/).


The most common types of recommendation systems are content based and collaborative filtering recommender systems.



## 1) Content based

Content based systems use meta data such as genre, producer, actor, musician to recommend items say movies or music. Content based systems are based on the idea that if you liked a certain item you are most likely to like something that is similar to it. This content based recommended system uses the matrix factorization with LDA (Latent Dirichlet Allocation).


## 2) Collaborative filtering


There are two types of collaborative models Memory-based methods and Model-based methods.The advantage of memory-based techniques is that they are simple to implement and the resulting recommendations are often easy to explain. They are divided into two:

#### a) User-based collaborative filtering
 In this model products are recommended to a user based on the fact that the products have been liked by users similar to the user.

#### b) Item-based collaborative filtering
 These systems identify similar items based on users’ previous ratings.


In this folder, there is a simple item-based collaborative filtering recommender system built with python. In collaborative filtering, the behavior of a group of users is used to make recommendations to other users. This case identifies similar items based on users’ previous ratings.

The Pearson correlation coefficient is used to determine the correlation between the users' ratings of two movies. This number will lie between -1 and 1. 1 indicates a positive linear correlation, -1 indicates a negative correlation and 0 indicates no linear correlation. 

------------------
To run the jupyter notebooks, a folder named "data" needs to be placed with the following files inside: movies.csv, ratings.csv, tags.csv, users.csv



