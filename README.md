# Movies-ETL
ETL process pipeline.
Extract data files clean and parse data.
Send the clean data to database. 
Movies data and Raings data read, clean and send to datbase.
 
## The data from the movies_df DataFrame replaces the current data in the movies table in the SQL database.
![movies_query.png](https://github.com/deepayogesh/Movies-ETL/blob/901f293fc7ce9aa03371a7a06aac42d17ebc9346/movies_query.png)

## The data from the MovieLens rating CSV file is added to the ratings table in the SQL database
![ratings_query.png](https://github.com/deepayogesh/Movies-ETL/blob/901f293fc7ce9aa03371a7a06aac42d17ebc9346/ratings_query.png)