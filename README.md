# ETL-Challenge Final Report

Extract: Original Datasources from Kaggle, CSV and SQlite data formatted. Looked to use Spotify and Pitchfork data for joining into a a few different tables.


Transform: had to create engine for pitchfork, store spotify data into DF with select columns. 


Load: Used Pandas to load dataframes into the PostGresSQL database after connecting to local database. This resulted in content, genres, Review, Artist, Labels, and Top 10 Tables.
