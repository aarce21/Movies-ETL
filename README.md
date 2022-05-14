# Movies-ETL
# Overview
The purpose of the Movies-ETL analysis was to assist in creating a data pipeline that can clean data, transform it, and load the data by connecting code run in jupyter notebook to a database in PostgreSQL. This analysis consisted of refactoring code used previously to produce new data files and merge data. This data was then loaded in a database and created tables in PostgreSQL. 

Resources used to perform this analysis include a Wikipedia JSON file, movies_metadata.csv file, and a ratings.csv file

# Results 
After running the analysis, two tables were created in PostgreSQL. 

The first table, a movies table, consists of 31 columns and 6,052 rows of data. Data that can be found in this table includes movie title, the budget, producers, directors, and a link to the films wikipedia page. 
![movies_query](https://github.com/aarce21/Movies-ETL/blob/main/Resources/movies_query.PNG)

The second table produced in the analysis is the ratings table. This table consists of all the information found in the movies table but also includes the movies rating out of 5 stars. 
![ratings_query](https://github.com/aarce21/Movies-ETL/blob/main/Resources/ratings_query.PNG)
