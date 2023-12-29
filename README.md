**Overview**

This project is a basic movie recommendation system using Item-based Collaborative Filtering and the K-Nearest Neighbors (KNN) algorithm. 

**Introduction**

In the entertainment world today, the movie recommendation system makes use of collaborative filtering to creates a similarity between the user and items and exploits these similarities to make recommendations. This techniques allows for movie suggestions that aligns with the user's taste and tailored for each users therefore improving their movie-watching experience. We have the User based collaborative filtering and the Item based collaborative filtering but this project is focused on the item (movie) based collaborative filtering which explores the relationships between items(movies) and recommends movies based on similarity between these movies.


**Dataset**

The datasets describe ratings and movies from MovieLens, a movie recommendation service. It contains 20,000,263 ratings across 27,262 movies. These data were created by 138,493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016. Users were selected at random for inclusion. 


**K-Nearest Neighbors (KNN) Algorithm**

How this works is the K-nearest neighbors algorithm is employed to identify similar items (movies) by analyzing their features (ratings). The key mechanism involves utilizing the cosine of the angles between the movies to gauge their similarity. A smaller angle signifies that, based on their features, the movies are aligned in the same or nearly the same direction, indicating a higher degree of similarity between the movies.

This project explores the use of knn-recommender system to find the 10 most closely related movies to a randomly selected movie.



