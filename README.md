# Recommender System: Project Overview
* Built a recommender system that takes a movie name as input from user and uses cosine similarity to recommend similar movies.
* Acquired dataset from kaggle and loaded it into a dataframe.
* Wrangled the data into two columns namely 'Title' and 'Key Notes'(containing all the other columns).
* Tokenized 'Key Notes' column using CountVectorized fit_transform function and stored the result in a matrix.
* Used the resultant matrix to find the cosine similarities.
* Used cosine similarities between movies to recommend new movies.


# Code and Resources Used
* **language**: Python
* **Packages**: numpy, pandas, sklearn(CountVectorizer, cosine_similarity)
* **dataset**: https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney
