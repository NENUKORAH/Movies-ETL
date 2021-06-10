# Movies-ETL

## Project Overview

Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs my help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 

I need to refactor the code from this module to create one function that takes in the three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data, and performs the ETL process by adding the data to a PostgreSQL database.

Note: The project overview is extracted from the background information in the module challenge.

### Resources

**Data Sources:** wikipedia.movies.json, movies_metadata.csv, ratings.csv, movies_query.png, ratings_query.png.

**Code Files:** ETL_function_test.ipynb, ETL_clean_wiki_movies.ipynb, ETL_clean_kaggle_data.ipynb ETL_create_database.ipynb.

**Software:** Visual Studio Code 1.56.0, PostgreSQL 13, pgAdmin4 v 5.0.

## Project Results

The ratings data, kaggle data, and wikipedia data were successfully read, extracted, transformed and loaded to the PostgreSQL database.

See the screenshots below of the database and query results;

![database_tables](https://user-images.githubusercontent.com/81701640/121609503-05cdbc00-ca22-11eb-88e0-2fdd4be6f2af.PNG)

![ratings_query](https://user-images.githubusercontent.com/81701640/121609505-06665280-ca22-11eb-93a4-0bb5372737e8.PNG)

![movies_query](https://user-images.githubusercontent.com/81701640/121609506-06665280-ca22-11eb-89e7-95559e5c14a8.PNG)

**Nnaemeka Enukorah**

**12th June, 2021**