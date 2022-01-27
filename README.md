## _Movie Recommendation Systems_
Recommendation System is a filtration program whose prime goal is to predict the “rating” or “preference” of a user towards a domain-specific item or item. In our case, this domain-specific item is a movie, therefore the main focus of our recommendation system is to filter and predict only those movies which a user would prefer given some data about the user him or herself.
- Popularity based recommendation engine
- Content based recommendation engine : https://share.streamlit.io/deepansha14/recommendation-systems/app.py
- Collaborative filtering based recommendation engine

## Installation
#### 1. Download the repository
```sh
$ git clone https://github.com/deepansha14/Recommendation-systems.git
```
> Data
We will use subset of 5000 TMDB Dataset. It is a mixture of movies from various websites with the rating that users gave after watching the movie.
- It contains of two files, tmdb_5000_credits.csv and tmdb_5000_movies.csv
- The tmdb_5000_credits.csv contains _movie_id,title,cast,crew_
- The tmdb_5000_movies.csv contains _budget,genres,homepage,id,keywords,original_language,original_title,overview,popularity,production_companies, production_countries,release_date,revenue,runtime,spoken_languages,status,tagline,title,vote_average,vote_count_

#### Get the data here:
```sh
$ wget https://www.kaggle.com/tmdb/tmdb-movie-metadata
```


