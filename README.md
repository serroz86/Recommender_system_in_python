# Recommender systems using python
Recommender systems in python using the MovieLes Dataset.

The most common types of recommendation systems are content based and collaborative filtering recommender systems.



## 1) Content based

Content based systems use meta data such as genre, producer, actor, musician to recommend items say movies or music. Content based systems are based on the idea that if you liked a certain item you are most likely to like something that is similar to it. This content based recommended system uses the matrix factorization with LDA (Latent Dirichlet Allocation).


## 2) Collaborative filtering


There are two types of collaborative models Memory-based methods and Model-based methods.The advantage of memory-based techniques is that they are simple to implement and the resulting recommendations are often easy to explain. They are divided into two:

#### a) User-based collaborative filtering
 In this model products are recommended to a user based on the fact that the products have been liked by users similar to the user. For example if Derrick and Dennis like the same movies and a new movie comes out that Derick likes,then we can recommend that movie to Dennis because Derrick and Dennis seem to like the same movies.

#### b) Item-based collaborative filtering
 These systems identify similar items based on users’ previous ratings. For example if users A,B and C gave a 5 star rating to books X and Y then when a user D buys book Y they also get a recommendation to purchase book X because the system identifies book X and Y as similar based on the ratings of users A,B and C.


In this folder, there is a simple Item-based collaborative filtering recommender system built with python. In collaborative filtering, the behavior of a group of users is used to make recommendations to other users. This case identifies similar items based on users’ previous ratings.

The Pearson correlation coefficient is used to determine the correlation between the users' ratings of two movies. This number will lie between -1 and 1. 1 indicates a positive linear correlation, -1 indicates a negative correlation and 0 indicates no linear correlation. 



