# Movie-Recommendation-System

# Project Description
Create a content-based movie recommeder that the user can give amovie title as input and the system return the 5 most relevant movie titles. We are going to use the genre of the movice and movie overviews to preprocess the data like remove punctuation, tokenization, remove stop words, and lemmitization. Then we used TF-IDF to identify the most important features or attributes of movies that are likely to be relevant to users' preferences. And we used consine similarities to compute the similarity between a user's preferences and the attributes of different movies calculated the similarity scores for all pairs of movies, we can use them to generate recommendations for the input from users.

# data dictionary
## 1. tmdb_5000_movies.csv
movie_id - A unique identifier for each movie.

title - Title of the movie.

cast - The name of lead and supporting actors.

crew - The name of Director, Editor, Composer, Writer etc..

## 2. tmdb_5000_credits.csv
budget - The budget in which the movie was made

genres - The genres of the movie, Action, Comedy ,Thriller etc.

homepage - A link to the homepage of the movie

id - This is infact the movie_id as in the first dataset

keywords - The keywords or tags related to the movie

original_language - The language in which the movie was made

original_title - The title of the movie before translation or adaptation

overview - A brief description of the movie

popularity - A numeric quantity specifying the movie popularity

production_companies - The production house of the movie

production_countries - The country in which it was produced

release_date - The date on which it was released

revenue - The worldwide revenue generated by the movie

runtime - The running time of the movie in minutes

spoken_languages - The spoken languges in the movie

status - "Released" or "Rumored"

tagline - Movie's tagline

title - Title of the movie

vote_average - average ratings the movie recieved

vote_count - the count of votes recieved
