# Movies-ETL

## Overview 
In this project the ETL (Extract, Transform, Load) process was performed to extract movie data from Wikipedia and Kaggle, and load clean data into a movies PostgreSQL database. 

### Deliverable 1
An ETL function was created to read three data files; Wikipedia data, Kaggle metadata and MovieLens ratings. From there, three dataframes were created.

### Deliverable 2
The Wikipedia data was extracted and transformed using list comprehensions and regular expressions. Specifically box office, budget, release date and running time data were cleaned. Duplicates and null values were removed, and data was converted to the correct data types. 

### Deliverable 3 
The Kaggle metadata and MovieLens ratings data were extracted and transformed using list comprehensions and regular expressions.  Specifically box office, budget, release date and running time data were cleaned. Duplicates and null values were removed, and data was converted to the correct data types. After cleaning, the Wikipedia and Kaggle dataframes were merged to create a movies dataframe. The MovieLens rating data was then merged with the movies dataframe to create a movies with ratings dataframe. 

### Deliverable 4 
The movies dataframe and MovieLens rating data were added to a movies PostgreSQL database. The final movies table has 6051 rows, and the ratings table has 26,024,289 rows. 
