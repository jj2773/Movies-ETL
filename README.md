# Movies-ETL
## Background
The following data sources were utilized for this Challenge
* Movie Lens ratings.csv
* A JSON file consisting of scraped movie data from Wikipedia
* Kaggle movies_metadata.csv

The CSV files were larger than permitted by GitHub but can be obtained from Kaggle.
https://www.kaggle.com/rounakbanik/the-movies-dataset

## Deliverables
The following deliverables are building upon one another to reach the final product
* An ETL function that takes the three files
* Add to the function to ETL the Wikipedia Data
* Add to the function to ETL the Kaggle Metadata
* Lastly Create a Movie Database in Postgres from the Python Pandas Dataframes

The below images confirm the tables in Postgres via a PGAdmin Query of counts

![alt text](https://github.com/jj2773/Movies-ETL/blob/main/Resources/movies_query.PNG)

![alt text](https://github.com/jj2773/Movies-ETL/blob/main/Resources/ratings_query.PNG)

