# Netflix Dataset Analysis

## Overview

This project analyzes a dataset containing movies and TV shows available on Netflix as of 2022. The analysis aims to extract interesting facts and insights regarding the content available on the platform. The dataset includes information such as titles, release dates, runtimes, cast and crew details, production companies, IMDb scores, and more.

## Project Goals

- **Data Transformation**: Convert the dataset into a suitable format for PostgreSQL.
- **Data Modeling**: Design a relational schema and create an Entity-Relationship (ER) model for efficient data organization.
- **Querying**: Execute various PostgreSQL queries to derive insights, including top-rated movies, popular genres, and actor appearances.
- **Indexing**: Implement indexing to enhance query performance and data retrieval efficiency.

## Dataset

The project utilizes the following datasets:

1. **raw_titles.csv**: Contains details of Netflix movies and shows (e.g., title, type, release year, age certification, runtime, genres, production countries, IMDb score, and votes).
2. **raw_credits.csv**: Information on the cast and crew for each movie/show (e.g., name, character, role).
3. **Best Shows Netflix.csv**: A list of the best TV shows based on IMDb scores and votes.
4. **Best Show by Year Netflix.csv**: The best TV show for each year based on IMDb scores and votes.
5. **Best Movies Netflix.csv**: The best movies based on IMDb scores and votes.
6. **Best Movies by Year Netflix.csv**: The best movie for each year based on IMDb scores and votes.


### Installation


1. **Set up the PostgreSQL Database**:
   - Create a new database in PostgreSQL.
   - Import the dataset CSV files into the corresponding tables as defined in the project’s DDL statements.

2. **Run DDL Statements**:
   Execute the provided DDL statements to create the necessary tables and constraints in your PostgreSQL database.

### Data Insertion

After creating the tables, use the provided DML statements to insert data from the CSV files into the respective tables.

## Queries

The project includes various SQL queries to extract insights from the dataset, including:

1. Top 10 years with the highest number of movies released.
2. Average IMDb scores for movies and shows.
3. List of best movies by genre.
4. Top directors by the number of movies in the best movies category.
5. And many more...

Refer to the SQL query section in the project report for detailed queries.

## Indexing

The project demonstrates the creation of indexes to improve query performance. The indexing details and the effects of indexing on query execution time are discussed in the project report.

## Conclusion

This analysis provides valuable insights into the Netflix content catalog, highlighting trends, popular genres, and key contributors to successful movies and shows. 


## Acknowledgments

- Dataset sourced from [Netflix](https://www.kaggle.com/datasets/thedevastator/the-ultimate-netflix-tv-shows-and-movies-dataset/data).

