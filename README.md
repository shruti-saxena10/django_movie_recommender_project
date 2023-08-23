# Django_movie_recommender
Movie Recommender with Django

This personal movie recommender is based on Django Framework.In this project, I have used content filtering based algorithm that would try to recommend unwatched/new movies to me if they are similar to my watched movies.

Content filtering based: The content filtering based recommendation algorithms assume that I may like a new movie if I have watched very similar movies before or based on our user profile it will try to find new movies matching my profile.

Jaccord similarity has been for finding the  similarity between the movies,I have measured the similarity of two movies by comparing their genres. For example, if I have watched Action-comedy movies, I am very likely to watch other popular Action-comedy movies.
