# Movies ETL 

## Overview:
We will perform the Extract-Transform-Load tasks to prepare a clean dataset for a hackethon to predict movie popularity.

## Summary:

### Extract
Our movie data is extracted from Wikipedia and Kaggle in three seperate files: <br>

* [wikipedia-movies.json](Resources/wikipedia-movies.json) containts information of movies between 1990 and 2018

* [ratings.csv](https://www.kaggle.com/rounakbanik/the-movies-dataset/download) can be downloaded from Kaggle.  Kaggle pulls this file from the MovieLens dataset of over 20 million reviews.

* [movies_metadata.csv](Resources/movies_metadata.csv) is pulled from Kaggle.  This file containts data from [The Movie Database (TMDb)](https://www.themoviedb.org/)

### Transform
We first tested our transform code for the Wikipeda data in [ETL_clean_wiki_movies.ipynb](ETL_clean_wiki_movies.ipynb)


We then added transform code for data from Kaggle and merged the data in [ETL_clean_kaggle_data.ipynb](ETL_clean_kaggle_data.ipynb)

### Load
We included code to load our clean and merged dataset into a SQL database in 
[ETL_create_database.ipynb](ETL_create_database.ipynb)

